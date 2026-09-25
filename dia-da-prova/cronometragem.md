# Cronometragem das baterias

A cronometragem registra a passagem dos pilotos volta a volta, monta a classificação da bateria e permite publicar o resultado no Race Manager.

Use este guia depois de revisar a [ordem das provas](ordem-e-baterias.md) e, quando duas categorias correrem juntas, as [categorias mescladas](categorias-mescladas.md).

## Antes de começar

Para usar a cronometragem, é necessário:

- ter um evento ativo;
- acessar como organizador ou cronometrista;
- possuir permissão para cronometrar e enviar resultados;
- usar uma [regra de número da moto](../organizacao-do-evento/categorias-pacotes-e-regras.md) que permita cronometragem.

A cronometragem fica disponível nas regras **Único por categoria** e **Duplicado com adesivo colorido**. Na regra **Duplicado sem cronometragem**, use o [lançamento manual de resultados](resultados-manuais.md).

Se uma opção não aparecer para a sua conta, consulte [perfis e permissões](../comecando/perfis-e-permissoes.md).

## Acessar as baterias

- Como organizador, abra **Cronometrista** no início do sistema.
- Como cronometrista, a lista de baterias do evento ativo é aberta na tela inicial.

As baterias aparecem na sequência definida em **Categorias → Ordem das Provas**. Treinos, manutenções, premiações e outros intervalos da programação não aparecem nessa lista.

Cada cartão representa uma bateria:

| Tipo | Como aparece |
| --- | --- |
| Bateria individual | Mostra uma categoria e a quantidade de pilotos inscritos. |
| Bateria mesclada | Mostra a indicação **Bateria mesclada**, os nomes das duas categorias e a quantidade total de pilotos. |

Na bateria mesclada, o piloto inscrito nas duas categorias aparece uma única vez para a cronometragem.

## Entenda a situação da bateria

| Situação | Significado |
| --- | --- |
| Sem indicação | A bateria ainda não possui classificação concluída nem resultado publicado. |
| **Cronometrado - aguardando envio** e **Pendente** | A classificação foi concluída neste dispositivo, mas ainda não foi publicada. |
| **Resultados enviados** e **Enviado** | O resultado está publicado no Race Manager. |

Um resultado pendente fica salvo somente no dispositivo usado para cronometrar. Ele não aparece em outro celular ou computador e ainda não está disponível como resultado publicado.

Por isso:

- continue no mesmo dispositivo até enviar o resultado;
- não cronometre a mesma bateria ao mesmo tempo em dois dispositivos;
- confira a indicação **Enviado** antes de considerar o trabalho concluído.

## Conferir a bateria antes da largada

1. Na lista, selecione a bateria que será disputada.
2. Confira o nome da categoria ou das categorias mescladas.
3. Selecione **Cronometrar Voltas**.
4. Confira os pilotos, números de moto, adesivos e categorias apresentados.

Se a bateria estiver sem pilotos, confirme se existem inscrições ativas nas categorias correspondentes. Corrija a inscrição antes da largada; não tente compensar um piloto ausente usando o cadastro de outro participante.

## Registrar as passagens

Durante a prova, toque no cartão do piloto sempre que ele passar pelo ponto de controle. Cada toque registra uma nova volta para aquele piloto.

A tela apresenta:

- a última passagem registrada;
- a volta atual do líder;
- o total de passagens;
- a quantidade de voltas de cada piloto;
- o painel com a ordem das passagens em cada volta.

Use o número e o adesivo exibidos no cartão para confirmar o piloto antes de tocar, principalmente em uma bateria mesclada.

### Desfazer uma passagem

O botão **Desfazer** remove a última passagem registrada na bateria, independentemente do piloto.

Se o erro estiver em uma passagem anterior de um piloto específico:

1. mantenha pressionado o cartão do piloto;
2. selecione **Remover última volta**;
3. confirme a remoção.

A volta do líder e a ordem das passagens são atualizadas depois da correção.

## Informar DNS ou DNF

Mantenha pressionado o cartão do piloto para alterar a situação dele.

| Situação | Quando usar | Efeito |
| --- | --- | --- |
| **DNS** | O piloto estava inscrito, mas não largou. | Remove as voltas registradas para ele. O piloto não recebe colocação nem pode receber HoleShot. |
| **DNF** | O piloto largou, mas não concluiu a prova. | Mantém as voltas já registradas, mas o piloto fica sem colocação final. Se for elegível, pode manter o HoleShot. |
| **Reativar piloto** | O piloto foi marcado como DNS ou DNF por engano. | Volta a permitir o registro de passagens. |

Ao marcar como DNS um piloto que já possui voltas, o Race Manager pede confirmação antes de removê-las.

## Informar o HoleShot durante a cronometragem

Quando o HoleShot estiver habilitado para a bateria:

1. selecione o cartão **HoleShot**;
2. toque no piloto vencedor na grade.

Também é possível manter pressionado o cartão do piloto e selecionar **Marcar HoleShot**.

Em uma bateria mesclada, o sistema exige um vencedor para cada categoria aplicável. Se o piloto estiver inscrito e for elegível nas duas categorias, a seleção é aplicada às duas. Se ele participar de apenas uma delas, selecione depois o vencedor da categoria que continuar pendente.

Observe estas regras durante o preenchimento:

- um piloto DNS não pode receber HoleShot;
- um piloto DNF pode receber HoleShot se for elegível;
- um piloto inelegível para pontuação não pode ser selecionado naquela categoria;
- quando uma categoria não possui piloto elegível que tenha largado, o HoleShot não é exigido para ela.

As demais regras e os efeitos da pontuação serão detalhados no capítulo específico de HoleShot.

## Sair antes de concluir

Se você tentar sair com passagens registradas, o sistema informa que os dados serão salvos automaticamente.

Sair da tela:

- preserva a cronometragem neste dispositivo;
- permite continuar depois na mesma bateria;
- não conclui a classificação;
- não publica o resultado.

Ao retornar, confira a última passagem, o total registrado e a situação dos pilotos antes de continuar.

## Concluir a cronometragem

1. Depois da última passagem, selecione **Concluir**.
2. Se houver pilotos ativos sem nenhuma passagem, escolha uma das opções:
   - **Marcar DNS**, quando eles não largaram;
   - **Revisar**, para voltar e corrigir as passagens ou situações.
3. Preencha os vencedores de HoleShot que ainda forem exigidos.
4. Confira o total de passagens e a volta do líder.
5. Confirme em **Concluir**.

O Race Manager monta a classificação com estes critérios:

1. maior quantidade de voltas;
2. entre pilotos com a mesma quantidade, quem concluiu a última volta primeiro.

Depois da conclusão, você retorna à tela da bateria. A classificação está salva localmente, mas ainda não foi publicada.

## Revisar e ajustar a classificação

Confira toda a lista antes do envio. Para corrigir a ordem:

1. selecione **Ajustar Resultado**;
2. mova os pilotos pelas setas ou arraste pelo controle de movimentação;
3. revise o HoleShot, quando estiver habilitado;
4. selecione **Salvar**.

O salvamento do ajuste continua sendo local. Para corrigir DNS, DNF ou passagens, volte a **Cronometrar Voltas**, mantenha pressionado o piloto e faça o ajuste necessário antes de concluir novamente.

## Publicar o resultado

Quando a classificação estiver correta:

1. selecione **Enviar Resultados**;
2. aguarde o processamento;
3. volte à lista de baterias;
4. confirme as indicações **Resultados enviados** e **Enviado**.

**Concluir** e **Salvar** não publicam o resultado. A publicação acontece somente em **Enviar Resultados**.

Na bateria individual, o resultado pertence à categoria apresentada. Na bateria mesclada, o Race Manager recebe a ordem geral e gera separadamente a classificação de cada categoria. Um piloto só entra no resultado das categorias em que está inscrito.

A publicação atualiza as colocações e os pontos da prova, incluindo o HoleShot quando aplicável. As informações relacionadas à classificação da Copa também são recalculadas quando necessário.

### Se não souber se o envio terminou

Se houver falha de conexão ou a confirmação não aparecer:

1. volte à lista de baterias;
2. atualize a lista;
3. confira a situação da bateria.

- Se aparecer **Enviado**, não envie novamente.
- Se aparecer **Pendente**, abra a bateria no mesmo dispositivo, revise e tente **Enviar Resultados** novamente.

Não limpe os dados enquanto ainda estiver verificando o resultado do envio.

## Corrigir um resultado publicado

A correção depois do envio exige uma permissão adicional. Sem ela, os botões de alteração permanecem indisponíveis.

Com a permissão necessária, abra a bateria e escolha o procedimento adequado:

- para trocar apenas a ordem de chegada, use **Ajustar Resultado**, salve e envie novamente;
- para refazer a cronometragem, use **Cronometrar Voltas**, registre as novas passagens, conclua, revise e envie novamente;
- para corrigir DNS ou DNF, volte a **Cronometrar Voltas**, altere a situação do piloto, conclua e envie novamente;
- para corrigir o HoleShot, use **Cronometrar Voltas** ou **Ajustar Resultado**, salve a alteração indicada pela tela e envie novamente.

Enquanto a correção não for enviada, o resultado anterior continua publicado. Depois do novo envio, o Race Manager substitui a classificação e recalcula os dados relacionados.

## Limpar dados ou limpar resultados

As duas ações têm efeitos diferentes:

| Ação | Onde aparece | O que remove |
| --- | --- | --- |
| **Limpar dados** | Na tela de registro das voltas | Descarta a cronometragem local. Se já existe um resultado publicado, ele é mantido e recarregado. |
| **Limpar Resultados** | Na tela da bateria, depois da publicação | Remove o resultado publicado. Exige permissão adicional e confirmação. |

Use **Limpar dados** quando precisar abandonar as passagens que ainda não foram enviadas. Essa limpeza não pode ser desfeita.

Use **Limpar Resultados** somente quando a publicação realmente precisar ser retirada. Depois da remoção, será necessário preparar e enviar outro resultado para publicar novamente a classificação.

### Remoção em bateria mesclada

Em uma bateria mesclada, **Limpar Resultados** remove:

- o resultado geral da bateria;
- o resultado individual das duas categorias;
- os pontos vinculados a esses resultados.

Confira as duas categorias antes de confirmar. A remoção também deixa a bateria sem resultado publicado, permitindo depois [desfazer a mesclagem](categorias-mescladas.md), se necessário.

## Problemas comuns

| Situação | Como proceder |
| --- | --- |
| **Nenhum evento ativo** | Solicite ao organizador que confira qual evento está ativo. A cronometragem não trabalha sobre um evento histórico. |
| **Cronometragem desabilitada para este evento** | A regra **Duplicado sem cronometragem** está ativa. Use o [lançamento manual de resultados](resultados-manuais.md) ou solicite ao organizador a revisão da configuração antes da prova. |
| **Sem permissão para cronometrar este evento** | Solicite ao organizador a revisão das permissões da conta. |
| Bateria sem pilotos | Confira se existem inscrições ativas nas categorias da bateria. |
| Bateria não encontrada ou lista desatualizada | Atualize a lista. Se houve alteração de ordem ou mesclagem, confira novamente a bateria correta. |
| Falha ao carregar | Selecione **Tentar novamente**. Se continuar, confirme a conexão e solicite suporte. |
| Resultado pendente em outro dispositivo | Continue no dispositivo usado para registrar as passagens. O rascunho local não é transferido automaticamente. |
| Estado desconhecido depois do envio | Atualize a lista e use a indicação **Enviado** como confirmação antes de repetir a operação. |

## Eventos históricos

A cronometragem trabalha somente com o evento ativo. Em um evento histórico, use as áreas de consulta e relatórios disponíveis; não é possível iniciar, corrigir ou remover a cronometragem por esse modo.
