# Gerenciar inscrições

O cadastro de inscrições reúne os dados do piloto, as categorias, a identificação da moto e a condição de pagamento. O organizador e o gerente de inscrições podem realizar essa operação no evento ativo.

## Antes de começar

Confirme se:

- o evento correto está ativo;
- as categorias e os preços foram revisados;
- os pacotes estão vinculados às categorias correspondentes;
- a regra de número da moto está correta;
- a equipe que fará o atendimento possui acesso ao evento.

Consulte [Categorias, pacotes e regras do evento](../organizacao-do-evento/categorias-pacotes-e-regras.md) se ainda precisar preparar esses cadastros.

## Escolher o caminho correto

A tela inicial apresenta duas opções relacionadas às inscrições:

| Opção | Use para |
| --- | --- |
| **Inscrição** | Abrir diretamente o formulário de uma nova inscrição. |
| **Inscritos** | Consultar, filtrar, editar, imprimir termos, cancelar registros ou iniciar uma nova inscrição pela lista. |

## Criar uma nova inscrição

1. No evento ativo, abra **Inscrição**.
2. Informe o CPF e use a busca para localizar o piloto. Também é possível pesquisar pelo nome no campo **Nome do Piloto**.
3. Confira os dados carregados ou preencha o cadastro quando o piloto ainda não existir.
4. Informe o número da moto.
5. Abra **Categorias** e selecione pelo menos uma categoria.
6. Defina a condição de pagamento e confira o total calculado.
7. Selecione **Finalizar**.
8. Escolha se deseja imprimir o termo.
9. Depois de concluir, escolha entre iniciar outra inscrição ou retornar à tela anterior.

Também é possível abrir **Inscritos** e selecionar **Nova Inscrição**.

### Dados do piloto

Confira cuidadosamente as informações antes de continuar:

| Campo | Orientação |
| --- | --- |
| **CPF** | Informe os 11 dígitos. O CPF identifica o piloto dentro dos cadastros da organização. |
| **Nome do Piloto** | Use o nome que deve aparecer nas listas e nos relatórios. |
| **Data de Nascimento** | Informe uma data válida e não futura. |
| **Número da Moto** | Use um número inteiro entre 1 e 999. |
| **Patrocinadores** | Campo opcional para os nomes que devem acompanhar o piloto. |
| **Cidade** | Informe a cidade do piloto. |
| **Estado (UF)** | Use uma UF brasileira válida. |
| **Telefone** | Informe um número com DDD. |

Quando o CPF ou o nome localizar um piloto existente, o sistema preenche os dados disponíveis. Revise tudo antes de finalizar, principalmente o número da moto, que pertence à inscrição atual.

## Quando o piloto já está inscrito

Um piloto pode ter somente uma inscrição ativa no mesmo evento. Ao localizar alguém que já está inscrito, o Race Manager carrega a inscrição existente para edição.

Se o conflito for identificado somente ao salvar, o sistema oferece **Abrir inscrição**. Use essa opção em vez de tentar criar um registro duplicado.

Uma inscrição cancelada continua no histórico, mas não impede uma nova inscrição ativa para o mesmo piloto.

## Selecionar categorias e números de moto

1. Preencha primeiro o **Número da Moto** principal.
2. Se o piloto usar o mesmo número em todas as categorias, mantenha **Mais de uma moto por categoria** desativado.
3. Se os números forem diferentes, ative **Mais de uma moto por categoria**.
4. Abra **Categorias**.
5. Marque as categorias em que o piloto participará.
6. Quando estiver usando números diferentes, informe o número de cada categoria.
7. Confira a quantidade selecionada e escolha **Salvar**.

Categorias com resultado já publicado não aceitam novas inscrições. Quando uma categoria da inscrição já estiver protegida por resultado, ela aparece bloqueada para alterações que afetariam a identificação ou a participação do piloto.

### Conflitos de número

O comportamento depende da regra definida no evento:

| Regra do evento | O que acontece na inscrição |
| --- | --- |
| **Único por categoria** | Se o número já estiver em uso na categoria, informe outro número. |
| **Duplicado sem cronometragem** | O número pode se repetir e não é necessário escolher adesivo. |
| **Duplicado com adesivo colorido** | Se houver repetição, o sistema solicita uma das cores de adesivo ainda disponíveis. |

Quando o sistema solicitar uma cor, escolha uma das opções apresentadas e prossiga. Se nenhuma cor estiver disponível, será necessário alterar o número.

### Preço e pacotes

O Race Manager calcula o total depois da seleção das categorias. Quando existir um pacote aplicável, o sistema compara as combinações permitidas e usa o menor preço válido.

Não é necessário escolher manualmente qual pacote será usado. Confira o total exibido antes de finalizar.

## Definir se o piloto pontua na Copa

Quando o evento está vinculado a uma Copa, cada categoria selecionada apresenta a opção **Pontua na Copa**. Ela começa marcada.

Desmarque essa opção somente quando o piloto puder participar da prova, mas não puder receber pontos naquela categoria.

Nesse caso:

- o piloto mantém sua colocação oficial na prova;
- não recebe pontos de posição nem de HoleShot;
- não ocupa uma posição na ordem usada para distribuir os pontos;
- não participa do cálculo nem dos desempates da classificação da Copa naquela categoria.

A elegibilidade é definida separadamente para cada categoria e vale para todas as Copas das quais o evento participa.

### Alterar a elegibilidade depois do resultado

Se já existir resultado publicado, o sistema informa que a mudança recalculará os resultados e a classificação das Copas. Confira as categorias mostradas e confirme somente depois de revisar o impacto.

O vencedor atual do HoleShot não pode ser alterado para inelegível enquanto esse resultado existir. Antes, ajuste o vencedor do HoleShot para outro piloto elegível ou exclua o resultado correspondente.

## Informar a condição de pagamento

Na criação da inscrição:

- mantenha **Pagamento recebido** marcado somente se o valor já tiver sido recebido;
- para uma inscrição ainda não paga, desmarque **Pagamento recebido**;
- quando o pagamento tiver sido recebido, escolha **Dinheiro**, **PIX** ou **Cartão**;
- marque **Cortesia** quando não houver cobrança;
- use **Desconto** somente para uma redução manual concedida à inscrição;
- confira o **Total** antes de finalizar.

Pacote, desconto e cortesia não são a mesma coisa. O pacote é aplicado automaticamente pelas categorias escolhidas; o desconto é informado manualmente; a cortesia deixa a inscrição sem cobrança.

Registrar uma condição financeira no Race Manager não realiza nenhuma transação bancária. O controle detalhado de recebimentos e devoluções será apresentado na página de financeiro da inscrição.

## Consultar inscrições

1. Na tela inicial, abra **Inscritos**.
2. Use a busca geral para pesquisar por nome, CPF ou número da moto.
3. Se necessário, ajuste **Situação da inscrição** entre **Ativas** e **Canceladas**.
4. Use **Situação financeira** para localizar inscrições pagas, pendentes, isentas ou com devolução pendente.
5. Para uma busca mais específica, selecione **Mais filtros**.
6. Abra **Ver detalhes** no cartão do piloto para consultar os dados da inscrição.

Os filtros adicionais disponíveis são:

- nome;
- CPF;
- cidade;
- UF;
- categoria;
- número da moto.

Filtros diferentes são aplicados em conjunto. Se uma combinação não retornar registros, use **Limpar** ou remova os filtros avançados.

Nos detalhes aparecem os dados de contato, idade, patrocinadores, categorias, números, adesivos, elegibilidade para pontuação, situação financeira, total e desconto, quando aplicável.

A opção **Relatório de Participantes** gera a lista dos pilotos ativos do evento. Inscrições canceladas permanecem no histórico, mas não entram nesse relatório operacional.

## Editar uma inscrição

1. Abra **Inscritos** e mantenha **Ativas** em **Situação da inscrição**.
2. Marque a caixa de seleção da inscrição desejada.
3. Use o botão **Editar**, identificado pelo ícone de lápis.
4. Faça as alterações necessárias.
5. Selecione **Salvar**.
6. Revise as categorias adicionadas ou removidas e o impacto financeiro apresentado.
7. Se estiver correto, escolha **Salvar alteração**.
8. Quando necessário, marque **Gerar termo atualizado após salvar**.

A revisão informa se ficará algum valor a receber ou a devolver. Salvar a alteração não confirma automaticamente que o dinheiro foi recebido ou devolvido.

### Restrições depois de publicar resultados

Quando já existe resultado publicado, o sistema protege os dados usados para identificar o piloto e sua participação. Conforme o caso, não será possível:

- remover a categoria;
- alterar o número da moto ou o adesivo daquela categoria;
- alterar dados principais de identificação do piloto;
- adicionar o piloto a uma categoria que já possui resultado publicado.

A alteração de elegibilidade segue o fluxo de confirmação específico descrito anteriormente.

Se outra pessoa alterar a inscrição enquanto o formulário estiver aberto, o sistema pode solicitar que os dados sejam recarregados. Recarregue, revise o conteúdo atual e só então repita a alteração.

## Cancelar inscrições

Cancelar uma inscrição mantém o registro no histórico e retira o piloto da operação ativa.

### Cancelar uma inscrição

1. Abra **Inscritos** e localize a inscrição ativa.
2. Abra os detalhes e use **Cancelar inscrição**, ou marque a inscrição e use o botão de cancelamento.
3. Confira o nome apresentado na confirmação.
4. Leia o aviso sobre valores recebidos.
5. Confirme o cancelamento.

### Cancelar várias inscrições

1. Marque as inscrições desejadas ou use **Selecionar todos** para os registros carregados.
2. Use **Cancelar inscrições**.
3. Confira a quantidade apresentada e confirme.
4. Leia a mensagem final e consulte **Canceladas** para verificar o resultado de cada registro.

Um cancelamento em lote pode concluir alguns registros e recusar outros. Sempre confira a quantidade informada ao final.

### Regras do cancelamento

- somente inscrições ativas do evento ativo podem ser canceladas;
- o cancelamento é bloqueado quando uma das categorias já possui resultado publicado;
- valores recebidos não são devolvidos automaticamente;
- quando existir saldo a devolver, registre a devolução separadamente;
- a inscrição cancelada permanece disponível no filtro **Canceladas**;
- não existe reativação da mesma inscrição pela interface atual.

Se o piloto voltar ao evento depois do cancelamento, faça uma nova inscrição. Não tente alterar o registro cancelado.

## Imprimir o termo de inscrição

Depois de criar uma inscrição, o sistema pergunta se deseja imprimir o termo de responsabilidade e o comprovante.

Para imprimir novamente:

1. abra **Inscritos**;
2. selecione somente uma inscrição;
3. use **Imprimir termo**, identificado pelo ícone de impressão.

O termo contém dados pessoais do piloto. Não publique o arquivo nem use dados reais em imagens ou exemplos da documentação.

## Consultar inscrições de um evento histórico

Ao abrir **Inscritos** durante a consulta de um evento histórico, é possível pesquisar, filtrar, conferir detalhes, imprimir termos e consultar registros cancelados.

O cadastro operacional fica em modo somente leitura: não é possível criar, editar ou cancelar inscrições sem voltar ao evento ativo correspondente. As operações financeiras possuem regras próprias e serão explicadas no capítulo específico.

## Checklist antes de atender o próximo piloto

Confirme se:

- os dados pessoais foram revisados;
- o número da moto está correto em cada categoria;
- todas as categorias desejadas foram selecionadas;
- a opção **Pontua na Copa** corresponde à situação do piloto;
- pagamento, desconto ou cortesia foram informados corretamente;
- o total foi conferido;
- o termo foi impresso quando necessário.
