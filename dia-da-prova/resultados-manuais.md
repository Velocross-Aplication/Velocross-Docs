# Lançamento manual de resultados

O lançamento manual permite registrar a classificação quando o evento usa a regra **Duplicado sem cronometragem**. Nesse fluxo, o operador informa quem finalizou, quem não terminou, quem não largou e a ordem de chegada.

Use este guia depois de revisar a [ordem das provas](ordem-e-baterias.md) e, quando duas categorias correrem juntas, as [categorias mescladas](categorias-mescladas.md).

## Antes de começar

Para acessar o lançamento manual, é necessário:

- ter um evento ativo;
- usar a regra de número **Duplicado sem cronometragem**;
- possuir permissão para visualizar resultados manuais.

Organizadores e gerentes de inscrições encontram a opção **Lançamento manual de resultados** no início do sistema. Para o cronometrista, essa lista é aberta na tela inicial quando o evento não permite cronometragem.

As opções de publicação, edição e exclusão dependem das permissões da conta. Consulte [perfis e permissões](../comecando/perfis-e-permissoes.md) quando um botão esperado não aparecer.

Este fluxo não fica disponível em eventos históricos nem nas regras que usam [cronometragem por voltas](cronometragem.md).

## Entenda a lista de categorias

A tela apresenta uma opção para cada categoria do evento, seguindo a sequência da programação salva.

| Identificação | Significado |
| --- | --- |
| **Categoria simples** | A categoria disputa sua própria bateria. |
| **Bateria mesclada** | A categoria corre fisicamente junto com outra, mas mantém resultado e pontuação próprios. |

Quando a categoria pertence a uma mesclagem, o cartão também mostra o nome da bateria física. As duas categorias aparecem como itens separados na lista e precisam receber suas próprias classificações.

### Situações e ações

| Indicação | Significado |
| --- | --- |
| **Pendente** | A categoria ainda não possui resultado publicado. |
| **Lançado** | O resultado da categoria está publicado. |
| **Lançar resultado** | Abre uma categoria pendente para preenchimento. |
| **Editar resultado** | Abre um resultado publicado para correção. |
| **Visualizar** | Abre os dados em modo somente leitura. |

**Pendente** não significa que exista um rascunho salvo. Alterações ainda não publicadas permanecem somente enquanto a tela de preenchimento está aberta.

Categorias sem pilotos inscritos não podem ser abertas para lançamento.

## Conferir a categoria

1. Na lista, selecione a categoria desejada.
2. Confira se ela aparece como **Categoria simples** ou **Bateria mesclada**.
3. Em uma bateria mesclada, confira os nomes das duas categorias apresentados no cabeçalho.
4. Revise pilotos, números de moto, adesivos e categorias antes de preencher o resultado.

O resumo mostra a quantidade total de pilotos e quantos estão como finalizados, DNF, DNS ou pendentes.

Se a lista de participantes estiver incorreta, ajuste primeiro as [inscrições](../inscricoes/gerenciar-inscricoes.md). O resultado manual deve incluir todos os pilotos com inscrição ativa na categoria.

## Informar a situação dos pilotos

Escolha uma situação para cada piloto:

| Situação | Quando usar | Efeito no resultado |
| --- | --- | --- |
| **Finalizou** | O piloto concluiu a prova. | Entra na classificação e precisa ocupar uma posição. |
| **DNF** | O piloto largou, mas não terminou. | Fica registrado sem colocação. Pode receber HoleShot quando for elegível. |
| **DNS** | O piloto não largou. | Fica registrado sem colocação e não pode receber HoleShot. |

Todos os pilotos precisam receber uma situação antes da publicação. O sistema também exige pelo menos um piloto em **Finalizou**.

### Finalizar todos os pendentes

O botão **Finalizar pendentes** altera para **Finalizou** todos os pilotos que ainda estiverem em **Sem situação**.

Use essa opção somente quando todos eles realmente tiverem concluído a prova. Depois, revise cada nome e organize a ordem de chegada.

## Organizar a classificação

Os pilotos marcados como **Finalizou** aparecem em **Classificação**.

1. Use **Subir** ou **Descer** para ajustar uma posição por vez.
2. Se preferir, arraste o piloto pelo controle de movimentação.
3. Confira a numeração da primeira até a última posição.

Ao mudar um piloto de **Finalizou** para DNF ou DNS, ele deixa a classificação. Ao alterar de DNF ou DNS para **Finalizou**, ele entra no fim da lista e precisa ser colocado na posição correta.

As posições são geradas de forma sequencial pelo Race Manager. DNF e DNS nunca recebem colocação.

## Elegibilidade para pontuação

Todos os pilotos ativos precisam constar no resultado, inclusive os que estiverem [inelegíveis para pontuação](../inscricoes/gerenciar-inscricoes.md#definir-se-o-piloto-pontua-na-copa).

Um piloto inelegível:

- permanece na classificação de acordo com a ordem física de chegada;
- não recebe pontos de colocação nem de HoleShot;
- não ocupa uma posição na sequência usada para distribuir os pontos aos pilotos elegíveis;
- não pode ser escolhido como vencedor do HoleShot naquela categoria.

Por isso, não retire nem mude a posição física de um piloto apenas porque ele não pontua.

## Informar o HoleShot

Quando o evento possui pontos de HoleShot, a tela apresenta **Piloto do HoleShot**.

1. Defina primeiro a situação dos pilotos.
2. Selecione o vencedor entre os pilotos disponíveis.
3. Confira o número da moto e o adesivo antes de publicar.

Podem receber HoleShot:

- pilotos em **Finalizou**;
- pilotos DNF que sejam elegíveis para pontuação.

Não podem receber HoleShot:

- pilotos DNS;
- pilotos inelegíveis para pontuação.

Se todos os pilotos elegíveis estiverem como DNS, a tela informa que o HoleShot não é necessário para a categoria.

Em uma bateria mesclada, cada categoria possui sua própria seleção. O mesmo piloto pode receber o HoleShot nas duas categorias quando estiver inscrito e for elegível em ambas, mas deve ser selecionado separadamente em cada resultado. A escolha não é copiada automaticamente para a outra categoria.

As demais regras e os efeitos da pontuação serão detalhados no capítulo específico de HoleShot.

## Publicar o primeiro resultado

Antes de publicar, confirme que:

- todos os pilotos possuem uma situação;
- existe pelo menos um piloto em **Finalizou**;
- a ordem da classificação está correta;
- o HoleShot foi preenchido quando exigido;
- DNF e DNS foram usados corretamente.

Depois da revisão:

1. selecione **Publicar resultado**;
2. leia a confirmação de que o resultado se tornará oficial;
3. selecione **Publicar**;
4. aguarde a mensagem **Resultado salvo com sucesso**;
5. ao voltar à lista, confira a indicação **Lançado**.

O resultado publicado passa a alimentar colocações, relatórios, pontos e Copa.

## Categorias mescladas e pilotos compartilhados

A mesclagem representa a bateria física, mas não cria uma classificação geral no lançamento manual. Cada categoria mantém:

- sua própria ordem de chegada;
- suas posições;
- sua pontuação;
- seu vencedor de HoleShot.

Quando o mesmo piloto está inscrito nas duas categorias, a situação dele precisa ser igual em ambas. Ele não pode, por exemplo, estar como **Finalizou** em uma categoria e DNF na outra.

Se a alteração também afetar resultados já publicados da bateria, a tela apresenta um aviso e o botão pode mudar para **Salvar 2 categorias**.

Nesse caso:

1. confira quantas categorias serão atualizadas;
2. confirme o salvamento conjunto;
3. aguarde a conclusão da operação;
4. abra a outra categoria e revise sua classificação;
5. ajuste e salve novamente se a entrada do piloto em **Finalizou** tiver mudado a ordem esperada.

O salvamento conjunto é integral: se alguma categoria não puder ser validada, nenhuma das alterações é publicada.

Mesmo nesse salvamento, o HoleShot continua individual. Alterar o vencedor em uma categoria não muda a outra.

## Editar um resultado publicado

Uma conta com permissão de escrita pode selecionar **Editar resultado** para carregar a situação, a classificação e o HoleShot atuais.

1. Faça as correções necessárias.
2. Revise todos os pilotos e a ordem dos finalizados.
3. Observe se a tela informa que outras categorias serão afetadas.
4. Selecione **Salvar alterações** ou **Salvar 2 categorias**, conforme apresentado.
5. Confirme **Substituir**.

A classificação anterior é substituída. Relatórios, pontos e Copa são recalculados pelo sistema.

Para publicar ou editar, a conta precisa possuir as permissões de criação e atualização. Uma conta apenas com visualização abre a tela com a indicação **Somente leitura** e não recebe os controles de alteração.

## Alteração feita por outro operador

Antes de salvar, o Race Manager verifica se os resultados da bateria mudaram desde a abertura da tela.

Se aparecer a mensagem de que outro operador alterou o resultado:

1. não tente reproduzir a alteração sobre os dados antigos;
2. volte para a lista;
3. confirme **Descartar** se houver alterações locais;
4. abra novamente a categoria;
5. revise o resultado atualizado;
6. refaça somente as correções ainda necessárias.

Essa proteção evita substituir silenciosamente o trabalho de outra pessoa.

## Sair sem publicar

Ao tentar sair com mudanças não salvas, o sistema apresenta **Descartar alterações?**.

- Selecione **Descartar** somente se não precisar mais do preenchimento atual.
- Permaneça na tela para continuar a revisão antes de publicar.

O lançamento manual não mantém um rascunho para continuar depois. Ao descartar ou fechar a tela sem salvar, será necessário preencher novamente.

## Excluir um resultado

A exclusão exige uma permissão própria e fica disponível somente para resultados publicados.

1. Abra a categoria marcada como **Lançado**.
2. Selecione **Excluir resultado** no topo da tela.
3. Confira o nome da categoria.
4. Leia o aviso sobre colocações, pontuações, relatórios e Copa.
5. Confirme em **Excluir resultado**.

A exclusão remove somente o resultado da categoria selecionada. Em uma bateria mesclada:

- o resultado da outra categoria permanece publicado;
- o HoleShot da outra categoria permanece inalterado;
- a mesclagem continua existindo.

Para [desfazer uma mesclagem](categorias-mescladas.md), exclua individualmente todos os resultados publicados das duas categorias. Depois da exclusão, a categoria volta a aparecer como **Pendente**.

## Se os inscritos mudarem durante o preenchimento

O resultado precisa conter todos os pilotos ativos da categoria. Se uma inscrição for incluída, cancelada ou alterada enquanto a tela estiver aberta, o salvamento pode ser interrompido e a lista será recarregada.

Nesse caso:

1. confira novamente todos os participantes;
2. revise números, adesivos e elegibilidade;
3. defina a situação dos pilotos que estiverem pendentes;
4. reorganize a classificação;
5. tente publicar novamente.

## Problemas comuns

| Situação | Como proceder |
| --- | --- |
| Nenhum evento ativo | Solicite ao organizador que confira o evento ativo. O lançamento não funciona sobre um evento histórico. |
| **O lançamento manual não está disponível para a política deste evento** | O evento usa uma regra com cronometragem. Acesse **Cronometrista** ou revise a regra antes da prova. |
| Opção ou botão não aparece | Solicite ao organizador a revisão das permissões da conta. Visualização, escrita e exclusão são acessos diferentes. |
| **Sem pilotos inscritos** | Confira se a categoria possui inscrições ativas. |
| Pilotos em **Sem situação** | Defina Finalizou, DNF ou DNS para todos antes de publicar. |
| Nenhum piloto em **Finalizou** | Informe corretamente ao menos um piloto que concluiu a prova. |
| HoleShot não informado | Escolha um piloto elegível em Finalizou ou DNF, quando a seleção for exigida. |
| Situação divergente em categoria mesclada | Use a mesma situação para o piloto compartilhado em todas as categorias da bateria. |
| Resultado alterado por outro operador | Descarte a cópia antiga, reabra a categoria e revise os dados atuais. |
| Falha ao carregar | Selecione **Tentar novamente**. Se continuar, confira a conexão e solicite suporte. |

## Eventos históricos

O lançamento manual está disponível somente no evento ativo. Em um evento histórico, use as áreas de consulta e os relatórios disponíveis; não é possível publicar, editar ou excluir resultados por este fluxo.
