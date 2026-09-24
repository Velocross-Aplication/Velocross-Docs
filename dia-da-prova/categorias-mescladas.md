# Categorias mescladas

A mesclagem permite que duas categorias disputem a mesma bateria física. O Race Manager reúne os pilotos para a operação da prova, mas mantém inscrições, colocações, pontuação e relatórios separados por categoria.

Faça a mesclagem antes de concluir a [ordem das provas e a programação](ordem-e-baterias.md). Assim, a bateria conjunta já poderá ser posicionada corretamente e os intervalos poderão ser revisados.

## Antes de começar

Para criar ou desfazer uma mesclagem, é necessário:

- ter um evento ativo;
- acessar como organizador ou gerente de inscrições;
- possuir permissão para atualizar inscrições;
- trabalhar com exatamente duas categorias por bateria mesclada.

A opção **Mesclar Categorias** não fica disponível durante a consulta de um evento histórico.

## Entenda a tela

A tela **Mesclar Categorias** é dividida em duas áreas:

| Área | O que mostra |
| --- | --- |
| **Mesclagens ativas** | Baterias mescladas já criadas, quantidade de pilotos e inscrições de cada categoria. |
| **Categorias disponíveis** | Categorias do evento que ainda não pertencem a uma mesclagem. |

Uma categoria marcada como **Finalizada** já possui resultado e não pode ser selecionada. Uma categoria marcada como **Sem inscritos** precisa receber ao menos uma inscrição ativa antes da mesclagem.

## Criar uma bateria mesclada

1. No início do organizador ou do gerente de inscrições, abra **Mesclar Categorias**.
2. Em **Categorias disponíveis**, selecione as duas categorias que correrão juntas.
3. Confira os nomes apresentados no botão **Mesclar** na parte inferior da tela.
4. Selecione **Mesclar** para abrir a prévia.
5. Na prévia, confira:
   - o nome da bateria;
   - o total de **Pilotos na bateria**;
   - a quantidade de inscrições em cada categoria.
6. Se aparecer **Pronto para mesclar**, selecione **Confirmar mesclagem**.
7. Aguarde a confirmação **Mesclagem criada**.

A quantidade de pilotos pode ser menor que a soma das inscrições. Isso acontece quando o mesmo piloto está inscrito nas duas categorias e aparece uma única vez na bateria física.

## Requisitos para concluir a mesclagem

A prévia só permite a confirmação quando:

- foram selecionadas duas categorias diferentes;
- as duas pertencem ao evento ativo;
- cada categoria possui ao menos uma inscrição ativa;
- nenhuma categoria possui resultado publicado;
- nenhuma categoria já pertence a outra mesclagem;
- números de moto e adesivos permitem identificar os pilotos corretamente.

Quando algum requisito não é atendido, a prévia apresenta **Não é possível mesclar** e mantém a confirmação bloqueada.

## Regras de identificação dos pilotos

A validação depende da [regra de número da moto](../organizacao-do-evento/categorias-pacotes-e-regras.md) configurada no evento.

| Regra do evento | Comportamento na bateria mesclada |
| --- | --- |
| **Único por categoria** | Números iguais que eram válidos em categorias separadas podem entrar em conflito quando pilotos diferentes passam a correr juntos. Altere o número de um deles antes de mesclar. |
| **Duplicado com adesivo colorido** | A identificação considera o número e o adesivo. Pilotos diferentes não podem ficar com o mesmo número e a mesma cor, nem ambos com o mesmo número sem adesivo. |
| **Duplicado sem cronometragem** | Números repetidos são permitidos. A mesclagem organiza a bateria física, e os resultados continuam pelo lançamento manual. |

O Race Manager não altera números ou adesivos automaticamente.

## Mesmo piloto nas duas categorias

Quando o mesmo piloto está inscrito nas duas categorias, ele aparece uma única vez na bateria. Para isso, precisa usar a mesma identificação nas duas categorias da inscrição:

- o mesmo número de moto;
- o mesmo adesivo, quando houver.

Se os dados forem diferentes, a prévia mostra **Mesmo piloto com dados diferentes**. Use a correção oferecida pelo sistema para escolher uma identificação compatível antes de confirmar a mesclagem.

Mesmo aparecendo uma vez na bateria, o piloto continua participando separadamente de cada categoria em que estiver inscrito.

## Corrigir um conflito de identificação

A prévia pode mostrar **Identificação visual duplicada** ou **Mesmo piloto com dados diferentes**.

Para corrigir:

1. Expanda o grupo de conflitos, se necessário.
2. Localize o piloto e a categoria indicados.
3. Selecione **Corrigir inscrição**.
4. Altere o número ou o adesivo permitido pela regra do evento.
5. No caso do mesmo piloto nas duas categorias, aplique uma identificação compatível às duas.
6. Selecione **Salvar correção**.
7. Aguarde o retorno à prévia e a nova validação.
8. Quando aparecer **Pronto para mesclar**, selecione **Confirmar mesclagem**.

A correção altera permanentemente a inscrição. Ela não vale somente para aquela bateria. Antes de salvar, confirme o novo número ou adesivo com a equipe de inscrições e com o piloto.

Alguns campos podem permanecer bloqueados quando já existe resultado publicado ou quando a regra do evento não permite aquela alteração. Nesse caso, a própria prévia informa o motivo. Não tente contornar o bloqueio criando outra mesclagem.

Se precisar revisar o cadastro completo, consulte [gerenciar inscrições](../inscricoes/gerenciar-inscricoes.md).

## Outros impedimentos apresentados na prévia

| Mensagem ou situação | Como resolver |
| --- | --- |
| **Sem inscritos** | Cadastre ao menos uma inscrição ativa na categoria. |
| **Categoria já finalizada** | A categoria possui resultado publicado e não pode entrar em uma nova mesclagem. |
| **Categoria já mesclada** | Desfaça a mesclagem atual antes de formar outra combinação. |
| **Identificação visual duplicada** | Altere o número ou o adesivo de uma das inscrições indicadas. |
| **Mesmo piloto com dados diferentes** | Use a mesma identificação nas duas categorias do piloto. |
| **Sem permissão para esta ação** | Solicite ao organizador a revisão das permissões da conta. |

Depois de resolver o problema, volte a **Mesclar Categorias**, selecione novamente as duas categorias e confira uma nova prévia.

## O que muda depois da mesclagem

A mesclagem cria uma única bateria física para as duas categorias. Com isso:

- a bateria aparece como um item em **Ordem das Provas**;
- o cronometrista vê uma lista conjunta de pilotos quando a [cronometragem](cronometragem.md) está habilitada;
- no lançamento manual, a bateria física é identificada, mas cada categoria mantém seu próprio resultado;
- um piloto inscrito nas duas categorias aparece uma vez na ordem geral da bateria;
- a classificação é separada novamente por categoria;
- a pontuação é calculada por categoria;
- o HoleShot continua sendo atribuído por categoria quando estiver habilitado.

A mesclagem não transforma duas categorias em uma. Os cadastros, as inscrições e os relatórios continuam usando as categorias originais.

## Mesclagem em evento sem cronometragem

Quando a regra do evento é **Duplicado sem cronometragem**, a bateria mesclada continua sendo útil para representar quem corre junto e em qual posição ela aparece na programação.

Nesse caso:

- a tela do cronometrista permanece indisponível;
- o resultado é lançado manualmente;
- cada categoria mantém sua própria classificação;
- a bateria mesclada continua aparecendo na ordem das provas.

O procedimento de lançamento será detalhado no capítulo de resultados manuais.

## Desfazer uma mesclagem

1. Abra **Mesclar Categorias**.
2. Em **Mesclagens ativas**, localize a bateria.
3. Selecione **Desfazer mesclagem**.
4. Leia o aviso e confirme a operação.
5. Aguarde a mensagem **Mesclagem desfeita**.

O desfazimento não altera inscrições automaticamente. Os números e adesivos permanecem com os valores atuais.

As categorias voltam a ser provas separadas e recuperam a ordem relativa que possuíam individualmente.

## Quando não for possível desfazer

Uma mesclagem com resultado salvo não pode ser desfeita. Primeiro, o resultado da bateria precisa ser removido por uma conta com a permissão correspondente. Para resultados publicados pela cronometragem, consulte [cronometragem das baterias](cronometragem.md). A remoção no lançamento manual será detalhada no capítulo correspondente.

O sistema também pode impedir o desfazimento quando a separação deixaria identificações duplicadas dentro de uma categoria.

Nesse caso:

1. confira os pilotos indicados em **Conflito após desfazer**;
2. selecione **Corrigir inscrição**;
3. altere o número ou o adesivo permitido;
4. selecione **Salvar correção**;
5. confirme novamente **Desfazer mesclagem**.

Essa correção também é permanente. Se o campo necessário estiver bloqueado, mantenha a mesclagem e resolva primeiro o motivo apresentado pelo sistema.

## Revisar a ordem depois da alteração

Ao criar uma mesclagem, a nova bateria assume a posição da categoria que aparecia primeiro. Ao desfazer, as categorias recuperam sua ordem relativa.

Depois de criar ou desfazer:

1. abra **Categorias → Ordem das Provas**;
2. confira a posição da bateria ou das categorias separadas;
3. reposicione qualquer intervalo que tenha sido movido para o fim;
4. selecione **Salvar Ordem**.

Consulte o procedimento completo em [ordem das provas e programação](ordem-e-baterias.md).

## Eventos históricos

O gerenciamento de mesclagens é exclusivo do evento ativo. Durante a consulta de um evento histórico, use as áreas disponíveis apenas para conferir informações e resultados já registrados.
