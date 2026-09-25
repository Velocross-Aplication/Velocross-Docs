# Ordem das provas e programação do evento

A ordem das provas define a sequência das baterias no evento. Na mesma tela, você também pode inserir treinos, manutenções de pista, intervalos, premiações e outros momentos da programação.

Prepare essa sequência depois de conferir as [categorias, os pacotes e as regras do evento](../organizacao-do-evento/categorias-pacotes-e-regras.md). Se duas categorias forem correr juntas, faça primeiro a [mesclagem](categorias-mescladas.md) e deixe a revisão final da ordem para depois.

## Antes de começar

Para alterar a programação, é necessário:

- ter um evento ativo;
- acessar o Race Manager como organizador ou gerente de inscrições;
- ter acesso à área **Categorias**.

As opções disponíveis ainda dependem das permissões da conta. A alteração da ordem não fica disponível durante a consulta de um evento histórico.

## Entenda os itens da programação

A tela pode apresentar três tipos de item:

| Item | Como aparece | Efeito |
| --- | --- | --- |
| Categoria individual | Uma prova com o nome da categoria | Representa uma bateria com uma categoria. |
| Bateria mesclada | Uma prova com os nomes das duas categorias e a indicação **Bateria mesclada** | Representa duas categorias correndo juntas. |
| Intervalo da programação | Um item sem número de prova | Representa treino, manutenção, intervalo, premiação ou outro momento sem resultado. |

Uma bateria mesclada ocupa uma única posição na ordem. As categorias continuam separadas para inscrições, resultados, pontuação e relatórios.

Os intervalos não são baterias. Eles não possuem pilotos, resultados ou pontuação e não aparecem como itens para o cronometrista ou o narrador.

## Definir a ordem das provas

1. No início do organizador ou do gerente de inscrições, abra **Categorias**.
2. Selecione **Ordem das Provas**.
3. Confira se todas as categorias e baterias mescladas esperadas aparecem na lista.
4. Altere a sequência de uma destas formas:
   - arraste o item pelo controle de movimentação;
   - use **Subir**;
   - use **Descer**.
5. Revise a numeração das provas.
6. Selecione **Salvar Ordem**.
7. Aguarde a confirmação **Ordem das provas salva** antes de sair.

A ordem exibida é salva como um conjunto. Se outra alteração no evento tiver mudado as baterias, reabra a tela, confira os itens atuais e salve novamente.

## Adicionar um intervalo à programação

Na tela **Ordem das Provas**, use os botões acima da lista para iniciar um novo item:

- **Treino**;
- **Manutenção**;
- **Outro**.

Na janela de inclusão:

1. Selecione o **Tipo**. Estão disponíveis treino, manutenção, intervalo, premiação e outro.
2. Preencha a **Descrição** que será mostrada na programação.
3. Se desejar, informe a **Duração (min)** com um número maior que zero.
4. Selecione **Adicionar**.
5. Mova o novo item para a posição desejada.
6. Selecione **Salvar Ordem**.

Um intervalo pode ficar antes da primeira prova ou depois de qualquer bateria.

## Editar ou remover um intervalo

Para editar:

1. Selecione o cartão do intervalo.
2. Altere o tipo, a descrição ou a duração.
3. Selecione **Salvar** na janela.
4. Ajuste a posição, se necessário.
5. Selecione **Salvar Ordem**.

Para remover, use **Remover** no próprio item e depois selecione **Salvar Ordem**.

A exclusão só é concluída quando a programação inteira é salva.

## Como funciona a numeração

Somente as provas recebem número. Os intervalos ficam entre elas sem alterar a referência usada pela equipe.

Por exemplo, inserir uma manutenção antes da sétima prova não transforma essa bateria na oitava. Ela continua sendo apresentada como a sétima prova.

Essa regra mantém a mesma referência na ficha distribuída à equipe durante o evento.

## Onde a ordem é usada

Depois de salva, a sequência das baterias é usada:

- na [lista de provas da cronometragem](cronometragem.md);
- na lista do [lançamento manual de resultados](resultados-manuais.md), quando essa for a política do evento;
- em **Fichas da Prova**;
- nos relatórios que oferecem a opção **Ordem das Provas**.

Os intervalos são incluídos na ficha da ordem das provas, sem numeração. Eles não são enviados para a cronometragem e não aparecem como atividade para o narrador.

## Quando um intervalo for movido para o fim

Cada intervalo permanece associado à prova que vinha antes dele. Se essa prova deixar de existir individualmente — por exemplo, após uma mudança nas categorias ou a criação de uma bateria mesclada — o Race Manager preserva o intervalo e o move para o fim.

Nesse caso, o sistema avisa que o intervalo perdeu a prova em que estava.

1. Localize o item destacado no fim da lista.
2. Mova-o para a posição correta.
3. Revise os demais intervalos.
4. Selecione **Salvar Ordem**.

O sistema não consegue recuperar automaticamente a posição anterior porque a prova usada como referência não existe mais na mesma forma.

## Se apenas a ordem das provas for salva

A ordem das baterias e os intervalos são gravados em duas etapas. Por isso, pode aparecer uma mensagem informando que a ordem foi salva, mas os intervalos não.

Se isso acontecer:

1. não repita outras alterações sem conferir a tela;
2. reabra **Categorias → Ordem das Provas**;
3. confira a ordem que já foi salva;
4. revise os intervalos;
5. selecione **Salvar Ordem** novamente.

Se a mensagem continuar aparecendo, preserve a ordem exibida e solicite suporte antes de reorganizar o evento por outro meio.

## Ordem reaproveitada em outros eventos

Quando a ordem de um evento ativo é salva, ela também passa a orientar a sequência de categorias dos próximos eventos do mesmo organizador.

O reaproveitamento segue estas regras:

- categorias que também estiverem no novo evento mantêm a ordem conhecida;
- categorias novas entram no final, em ordem alfabética;
- ao ser ativado, cada evento mantém sua própria ordem;
- mudar a ordem de outro evento não altera uma sequência já preservada;
- ao reativar um evento que já tinha sua própria ordem, essa sequência é mantida;
- baterias mescladas não são copiadas para outro evento;
- treinos, manutenções e demais intervalos também não são copiados.

Por isso, mesmo quando a sequência inicial estiver correta, revise a programação de cada evento antes da prova.

## Alterações em categorias mescladas

Ao criar uma [bateria mesclada](categorias-mescladas.md), o grupo assume a posição da categoria que aparecia primeiro. Ao desfazer a mesclagem, as categorias recuperam sua ordem relativa individual.

Depois de qualquer uma dessas operações:

1. volte a **Categorias → Ordem das Provas**;
2. confira a posição da bateria ou das categorias separadas;
3. verifique se algum intervalo foi movido para o fim;
4. salve a programação revisada.

## Eventos históricos

Em um evento histórico, **Ordem das Provas** não é apresentada como opção de alteração. Use esse modo apenas para consultar as informações e os relatórios que continuarem disponíveis.

Para voltar a organizar a programação, trabalhe no evento ativo. Consulte também [eventos ativos e históricos](../organizacao-do-evento/eventos-ativos-e-historicos.md).
