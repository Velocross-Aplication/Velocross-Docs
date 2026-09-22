# Registro de divergências editoriais

Este arquivo apoia a manutenção da documentação e não faz parte da navegação pública do GitBook. O registro evita que um comportamento incompleto ou incompatível seja apresentado como disponível.

## Referências da análise

- Frontend: versão 1.3.0.
- Backend: versão 1.3.0.
- Análise inicial: 21 de setembro de 2026.

## Divergências abertas

### DOC-001 — Solicitações de inscrição sem acesso pelo menu

**Frontend:** existe uma tela para solicitações de inscrição, mas os atalhos de **Solicitações** estão comentados nos menus do organizador e do gerente de inscrições.

**Backend:** existem contratos e operações para listar, aprovar e rejeitar solicitações públicas.

**Decisão editorial:** não documentar o tratamento de solicitações como função disponível no aplicativo até que exista um caminho ativo na navegação e o fluxo seja validado de ponta a ponta.

### DOC-002 — “Deletar evento” arquiva o registro

**Frontend:** a lista usa os textos **Deletar evento** e “esta ação não pode ser desfeita”.

**Backend:** a operação correspondente altera o estado do evento para arquivado, sem realizar exclusão física imediata.

**Decisão editorial:** não publicar um procedimento de exclusão enquanto o nome, o efeito para o usuário e a possibilidade de recuperação não estiverem alinhados.

### DOC-003 — Rotas antigas no README do backend

**Frontend:** a cronometragem atual usa baterias, participantes e resultados por bateria.

**Backend:** o controlador atual também usa o fluxo por bateria, mas o README ainda lista rotas antigas por categoria e uma rota antiga de envio de resultados.

**Decisão editorial:** considerar o controlador e os contratos atuais de bateria como referência. Não usar a lista resumida do README do backend para descrever a navegação da cronometragem.

### DOC-004 — Edição visível em evento inativo

**Frontend:** a lista de eventos mantém o botão **Editar evento** visível para eventos inativos.

**Backend:** eventos inativos que já possuem inscrições são protegidos contra alteração. Os contratos orientam modo somente leitura para eventos históricos.

**Decisão editorial:** orientar consulta histórica como somente leitura e não ensinar edição de evento inativo. A reativação deve ser tratada como a forma explícita de voltar à operação.

### DOC-005 — Recuperação por e-mail para colaboradores

**Frontend:** a opção **Esqueci minha senha** aparece na tela de acesso, mas o formulário usado pelo organizador para criar gerente de inscrições, cronometrista ou narrador não solicita e-mail.

**Backend:** a recuperação envia o código ao e-mail da própria conta. Os perfis de colaborador criados pelo fluxo atual ficam sem e-mail.

**Decisão editorial:** orientar a recuperação por e-mail apenas para contas que possuem e-mail cadastrado. Colaboradores devem solicitar ao organizador a redefinição pela lista de usuários.

### DOC-007 — Seleção de pacotes no formulário do evento

**Frontend:** o formulário do evento mostra **Selecionar Pacotes**, envia uma lista de pacotes ao salvar e, ao editar, pode deduzir os pacotes a partir das categorias vinculadas.

**Backend:** os contratos de criação e edição do evento não recebem pacotes. O cálculo de preço considera os vínculos entre cada categoria e seus pacotes.

**Decisão editorial:** documentar que a aplicação de um pacote depende das categorias vinculadas dentro do cadastro do pacote ou da categoria. Não afirmar que marcar um pacote no formulário o vincula diretamente ao evento.

## Observações de navegação

### DOC-006 — Menu geral de relatórios sem atalho atual

Existe uma tela geral de relatórios no código do frontend, mas ela não está ligada aos menus iniciais atuais. Os relatórios alcançáveis estão distribuídos entre **Categorias**, **Financeiro**, inscrições e **Copa**.

**Decisão editorial:** documentar somente os caminhos que o usuário consegue abrir pela navegação atual.

### DOC-008 — “Excluir” usuário desativa a conta

**Frontend:** a lista de usuários exibe a ação **Excluir** e consulta somente colaboradores ativos. Depois da ação, a conta deixa de aparecer na lista e não existe uma opção de reativação na navegação atual.

**Backend:** a operação usada pelo aplicativo altera o estado da conta para desativado. Existe uma operação de reativação no contrato, mas ela não está disponível na interface atual.

**Decisão editorial:** descrever a ação como retirada ou desativação do acesso, sem afirmar que os dados são excluídos permanentemente. Alertar que a versão 1.3.0 não oferece reativação pelo aplicativo.

### DOC-009 — Tela de eventos por usuário sem acesso pela navegação

**Frontend:** existe uma tela de eventos por usuário no código, mas nenhum caminho da navegação atual abre essa tela. O cadastro e a edição de colaboradores não apresentam seleção de eventos.

**Backend:** os contratos atuais de criação e edição de colaboradores não recebem uma lista de eventos. Durante a operação, o colaborador acompanha o evento ativo do organizador.

**Decisão editorial:** não documentar atribuição de eventos por colaborador. Orientar que a equipe trabalha no evento ativo selecionado pelo organizador.

## Como encerrar uma divergência

Ao resolver um item:

1. registre a versão em que o comportamento foi alinhado;
2. descreva brevemente a solução adotada;
3. atualize ou crie a página pública correspondente;
4. valide os links e a navegação;
5. mova o item para uma seção de divergências resolvidas.
