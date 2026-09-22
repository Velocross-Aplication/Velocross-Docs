# Financeiro da inscrição

O financeiro da inscrição controla o valor contratado com cada piloto e registra recebimentos, devoluções e correções. Ele não movimenta dinheiro, não faz transferências e não substitui a conferência feita pela organização.

> Confirme um recebimento ou uma devolução somente depois que o dinheiro tiver sido movimentado fora do Race Manager.

## Quem pode usar

O organizador e o gerente de inscrições normalmente consultam o financeiro das inscrições. As ações exibidas dependem das permissões da conta:

- quem possui acesso de consulta pode visualizar saldos e histórico;
- quem possui acesso de confirmação pode registrar recebimentos, devoluções e correções.

Se o botão necessário estiver desabilitado ou não aparecer, confira o perfil da conta com o organizador.

## Financeiro da inscrição ou financeiro do evento

São áreas diferentes:

| Área | Para que serve |
| --- | --- |
| **Financeiro da inscrição** | Conferir e registrar os valores de um único piloto. |
| **Financeiro** da tela inicial | Consultar o resumo e as distribuições financeiras de todo o evento. |

Esta página trata somente do financeiro individual da inscrição. O fechamento consolidado será apresentado no capítulo de relatórios.

## Situação da inscrição e situação financeira

A situação operacional e a situação financeira são controles separados.

Uma inscrição pode estar:

- **Ativa:** o piloto continua inscrito no evento, mesmo quando existe valor a receber;
- **Cancelada:** o piloto foi retirado da operação, mas o histórico e eventuais devoluções permanecem disponíveis.

O estado financeiro pode ser:

| Situação exibida | Significado |
| --- | --- |
| **A receber** | Ainda existe saldo contratado que não foi registrado como recebido. |
| **Pago** | O valor contratado foi registrado como recebido e não há saldo pendente. |
| **Isento** | A inscrição não possui valor a cobrar, por cortesia ou desconto integral. |
| **Devolução pendente** | Existe valor recebido que deve ser devolvido. |
| **Sem pendências** | A inscrição cancelada não possui saldo a devolver. |
| **Histórico sem confirmação** | O registro antigo não possui informação suficiente para confirmar como a liquidação ocorreu. |

Uma inscrição **A receber** continua ativa e pode participar normalmente. O estado financeiro não substitui a situação operacional.

## Entender os valores

Na tela **Financeiro da inscrição**, o resumo apresenta:

| Valor | O que representa |
| --- | --- |
| **Contratado** | Obrigação financeira atual da inscrição. Em uma inscrição cancelada, a obrigação atual é zero. |
| **Recebido** | Total dos recebimentos registrados, considerando correções. |
| **Devolvido** | Total das devoluções registradas, considerando correções. |
| **Recebido líquido** | Valor recebido menos o valor devolvido. |
| **A receber** | Saldo completo que ainda falta receber. |
| **A devolver** | Saldo completo que ainda precisa ser devolvido. |

Use sempre os valores apresentados pelo sistema. Não calcule o saldo com base apenas na forma de pagamento ou no total antigo da inscrição.

## Definir a condição financeira ao criar a inscrição

Durante uma nova inscrição:

- **Pagamento recebido** começa marcado para contas autorizadas a confirmar pagamentos;
- mantenha a opção marcada somente quando o valor total já tiver sido recebido;
- escolha **Dinheiro**, **PIX** ou **Cartão** para registrar a forma do recebimento;
- desmarque **Pagamento recebido** quando o valor ainda estiver pendente;
- marque **Cortesia** quando não houver cobrança;
- use **Desconto** para uma redução manual do preço calculado.

O Race Manager não registra pagamentos parciais. Se apenas parte do valor foi recebida, não confirme o pagamento como concluído.

### Pacote, desconto e cortesia

Esses conceitos possuem efeitos diferentes:

- o **pacote** é aplicado automaticamente conforme as categorias e regras configuradas;
- o **desconto** reduz manualmente o preço calculado para aquela inscrição;
- a **cortesia** deixa a inscrição sem cobrança e não cria um recebimento.

Um desconto que reduza o total a zero também deixa a inscrição isenta, mas continua sendo um desconto, não uma cortesia.

Consulte [Gerenciar inscrições](gerenciar-inscricoes.md) para o procedimento completo de cadastro.

## Abrir o financeiro de uma inscrição

1. Na tela inicial, abra **Inscritos**.
2. Localize o piloto.
3. Abra **Ver detalhes** no cartão.
4. Selecione **Financeiro**.

Também é possível marcar somente uma inscrição e usar **Financeiro da inscrição**, identificado pelo ícone de carteira.

Use os filtros **Situação da inscrição** e **Situação financeira** para localizar inscrições ativas, canceladas, pendentes, pagas, isentas ou com devolução pendente.

## Confirmar um recebimento

Use esse procedimento somente quando o dinheiro já tiver sido recebido integralmente:

1. Abra o **Financeiro da inscrição**.
2. Confira o valor em **A receber**.
3. Selecione **Confirmar recebimento**.
4. Escolha a **Forma de recebimento**.
5. Confira novamente o saldo apresentado.
6. Selecione **Confirmar recebimento realizado**.
7. Aguarde a confirmação e verifique se a situação passou para **Pago**.

A confirmação registra todo o valor mostrado em **A receber**. Não é possível informar outro valor ou registrar somente uma parte do saldo.

Uma inscrição cancelada não aceita novo recebimento. Se ela possuir valor a devolver, use o procedimento de devolução.

## Confirmar uma devolução

Primeiro devolva o dinheiro ao piloto pelo meio definido pela organização. Depois registre a operação:

1. Abra o **Financeiro da inscrição**.
2. Confira o valor em **A devolver**.
3. Selecione **Confirmar devolução**.
4. Escolha a **Forma de devolução**.
5. Confira novamente o saldo apresentado.
6. Selecione **Confirmar devolução realizada**.
7. Aguarde a confirmação e verifique se não existe mais saldo a devolver.

A confirmação registra todo o valor mostrado em **A devolver**. Não confirme antes de realizar a devolução e não devolva um valor maior que o saldo apresentado.

A forma de devolução registra como o dinheiro foi devolvido. Ela não precisa alterar nem apagar o recebimento original.

## Entender o impacto de uma edição

Ao editar uma inscrição, o sistema preserva o preço já contratado para as categorias existentes. Novas categorias usam as regras atuais; categorias removidas respeitam o histórico de preço disponível.

A tela **Confirmar alterações** apresenta:

- categorias adicionadas ou removidas;
- valor atual e novo valor, quando houver mudança;
- saldo que ficará a receber;
- saldo que ficará a devolver;
- alterações de elegibilidade para pontuação;
- correções financeiras incluídas na mesma edição.

Confira esse resumo antes de selecionar **Salvar alteração**.

### Quando o valor aumenta

Depois de salvar, o sistema pode abrir **Registrar recebimento**. Registre a operação somente se o novo saldo já tiver sido recebido. Caso contrário, escolha **Receber depois**; a inscrição permanecerá com valor a receber.

### Quando o valor diminui

Depois de salvar, o sistema pode abrir **Registrar devolução**. Primeiro devolva o dinheiro. Depois confirme a operação. Se a devolução ainda não ocorreu, escolha **Devolver depois**; o saldo permanecerá pendente.

A alteração da inscrição e a confirmação financeira são operações separadas. Se a inscrição for atualizada, mas a confirmação financeira falhar ou for adiada, não repita a edição. Abra o financeiro e conclua somente a operação pendente.

## Cancelamento e saldo a devolver

Cancelar uma inscrição não devolve valores automaticamente.

Depois de um cancelamento individual, o sistema pode mostrar um aviso com o saldo e a opção **Registrar devolução**. Se não for possível concluir naquele momento, escolha **Agora não** e retorne depois pelo financeiro.

Para cancelamentos em lote:

1. abra **Inscritos**;
2. altere **Situação da inscrição** para **Canceladas**;
3. use **Situação financeira** para localizar **Devolução pendente**;
4. abra cada inscrição e registre a devolução realizada.

Uma inscrição que nunca teve valor recebido não gera devolução. O saldo deve ser conferido individualmente antes de qualquer movimentação.

## Consultar o histórico financeiro

A seção **Histórico financeiro** mostra cada recebimento ou devolução registrado. Ao expandir um lançamento, é possível consultar:

- tipo da operação;
- valor e forma de pagamento vigentes;
- valor e forma originalmente registrados;
- data e responsável disponíveis no histórico;
- revisões realizadas;
- indicação de registro corrigido ou presumido.

Os lançamentos originais não são apagados. Uma correção cria uma revisão e mantém a informação anterior para conferência.

Registros antigos marcados como **Presumido** não comprovam que o dinheiro foi efetivamente recebido. Use também os comprovantes mantidos pela organização.

## Corrigir um lançamento incorreto

Use **Corrigir lançamento** quando o valor ou a forma de pagamento foram registrados incorretamente no Race Manager. Uma correção não recebe nem devolve dinheiro.

1. Abra o **Financeiro da inscrição**.
2. Em **Histórico financeiro**, expanda o lançamento incorreto.
3. Selecione **Corrigir lançamento**.
4. Informe o valor correto.
5. Escolha a forma de pagamento correta quando o valor for maior que zero.
6. Descreva o motivo da correção.
7. Selecione **Aplicar ao formulário**.
8. Revise a proposta e escolha **Confirmar correções**.
9. Confira os novos saldos depois da confirmação.

O botão de correção aparece somente para lançamentos que podem ser corrigidos por esse fluxo.

### Escolher entre correção e devolução

| Situação | Ação correta |
| --- | --- |
| O dinheiro foi recebido, mas a forma foi registrada incorretamente. | Corrigir o lançamento. |
| Foi registrado um recebimento que não aconteceu. | Corrigir o recebimento para zero. |
| O dinheiro foi realmente devolvido ao piloto. | Confirmar uma devolução. |
| Um desconto foi concedido depois de um recebimento verdadeiro. | Editar o desconto e depois confirmar a devolução pendente. |
| Desconto ou cortesia e recebimento foram registrados incorretamente na mesma operação. | Editar a inscrição e corrigir o lançamento no mesmo formulário. |

Não anule um recebimento verdadeiro para esconder uma devolução devida. A devolução real deve permanecer registrada separadamente.

Quando dois lançamentos relacionados estiverem incorretos, aplique as correções necessárias antes de confirmar. O sistema valida o resultado final e pode recusar uma alteração que deixe o total devolvido maior que o recebido.

## Retomar uma operação com resultado desconhecido

Uma falha de conexão pode impedir o aplicativo de saber se o registro foi concluído. Nesse caso, aparece o aviso de que existe uma operação com resultado desconhecido.

Quando isso acontecer:

1. não receba nem devolva o dinheiro novamente;
2. não inicie outra confirmação para a mesma inscrição;
3. entre com a mesma conta que iniciou a operação;
4. abra novamente o financeiro;
5. use **Retomar operação confirmada anteriormente**;
6. aguarde a atualização dos saldos.

A retomada verifica a tentativa anterior e evita criar um lançamento duplicado. Se a tentativa foi iniciada por outra conta, peça ao usuário original para concluir a retomada.

## Financeiro em eventos históricos

Não é necessário reativar um evento apenas para conferir ou regularizar o financeiro.

Em um evento histórico da própria organização, conforme as permissões da conta, ainda é possível:

- consultar os saldos e o histórico;
- confirmar recebimento de uma inscrição que permanece ativa;
- confirmar uma devolução pendente;
- corrigir um lançamento permitido.

Não é possível receber novo pagamento de uma inscrição cancelada. O cadastro, as categorias e o cancelamento continuam bloqueados no modo histórico.

## Problemas comuns

| Situação | Como proceder |
| --- | --- |
| O botão de recebimento ou devolução não aparece. | Confira se existe saldo correspondente e se a conta possui permissão de confirmação. |
| A inscrição mudou enquanto a tela estava aberta. | Use **Atualizar**, revise os saldos e tente novamente. |
| A edição foi salva, mas a confirmação financeira falhou. | Não repita a edição; abra o financeiro e conclua o saldo pendente. |
| Existe uma operação com resultado desconhecido. | Não crie outra operação; use a retomada com a conta original. |
| Um registro antigo aparece sem confirmação. | Confira os documentos da organização e não presuma que o valor foi recebido ou devolvido. |

## Checklist financeiro

Antes de encerrar o atendimento, confirme:

- a inscrição e o piloto corretos estão abertos;
- o valor contratado está correto;
- recebimentos foram registrados somente depois de realizados;
- devoluções foram registradas somente depois de realizadas;
- a forma de pagamento ou devolução corresponde à operação;
- descontos e cortesias foram usados corretamente;
- nenhuma operação incerta foi repetida;
- eventuais correções possuem uma justificativa clara.
