# Categorias, pacotes e regras do evento

Categorias, pacotes, regra de número da moto e pontuação devem ser definidos antes do início da operação. Essas configurações controlam o valor calculado para a inscrição, a identificação dos pilotos e a forma de registrar os resultados.

A criação e a alteração desses cadastros são funções do organizador. Outros perfis podem visualizar categorias e informações do evento conforme suas permissões.

## Entenda cada configuração

| Configuração | Para que serve |
| --- | --- |
| Categoria | Representa a divisão em que o piloto se inscreve e possui um preço unitário. |
| Pacote | Define um preço para determinada quantidade de categorias vinculadas. |
| Regra de número da moto | Define se números podem se repetir e se a cronometragem estará disponível. |
| Regra de pontuação | Define os pontos por posição e, opcionalmente, o bônus de HoleShot. |

## Criar uma categoria

1. No início do organizador, abra **Eventos**.
2. Crie um evento ou use **Editar evento** em um evento que possa ser alterado.
3. Selecione **Selecionar Categorias**.
4. Selecione **Novo**.
5. Informe um nome que ainda não esteja em uso.
6. Informe o **Preço Unitário**.
7. Se a categoria participar de algum pacote já criado, use **Selecionar Pacotes** e marque os pacotes correspondentes.
8. Selecione **Salvar**.
9. Na lista de categorias, marque a nova categoria e salve a seleção.
10. De volta ao formulário, salve o evento.

O evento deve ter pelo menos uma categoria. O preço unitário deve ser maior que zero e será usado quando nenhum pacote aplicável gerar um valor menor.

## Editar uma categoria

Na lista aberta por **Selecionar Categorias**, use o botão de edição da categoria. É possível alterar o nome, o preço unitário e os pacotes vinculados.

Faça alterações de preço antes de iniciar as inscrições. O valor registrado em uma inscrição é calculado e armazenado no momento da operação; por isso, o preço atual do catálogo não deve ser usado isoladamente para conferir uma inscrição antiga.

## Remover do evento ou desativar no catálogo

Essas ações são diferentes:

- **Remover do evento:** desmarque a categoria em **Selecionar Categorias** e salve o evento. A categoria continua no catálogo para uso futuro.
- **Desativar:** quando a opção **Desativar** estiver disponível na lista de categorias, a categoria deixa de ficar disponível para novos vínculos.

Uma categoria vinculada ao evento ativo não pode ser desativada diretamente. Primeiro ela precisa ser removida do evento. A remoção é bloqueada quando existem inscrições ativas, resultados publicados ou uma bateria mesclada usando a categoria.

Uma categoria inativa que continuar vinculada pode ser preservada. Se ela for removida, não poderá ser adicionada novamente enquanto permanecer inativa.

## Criar um pacote

1. No formulário do evento, selecione **Selecionar Pacotes**.
2. Selecione **Novo**.
3. Informe o nome do pacote.
4. Preencha a primeira regra de preço.
5. Se precisar de outras faixas, use **Adicionar**.
6. Selecione **Selecionar Categorias** e marque as categorias às quais o pacote se aplica.
7. Selecione **Salvar**.

O pacote precisa ter pelo menos uma regra de preço. Ele pode ter até cinco regras.

> A aplicação do pacote depende das categorias vinculadas dentro do seu cadastro. Apenas marcar o pacote na lista aberta pelo formulário do evento não substitui esse vínculo.

Também é possível fazer o vínculo no sentido contrário: ao criar ou editar uma categoria, use **Selecionar Pacotes**.

## Configurar as faixas de preço

Cada regra do pacote possui:

- **Mínimo:** menor quantidade de categorias para a regra valer;
- **Máximo:** maior quantidade permitida na faixa;
- **Ilimitado:** remove o limite máximo;
- **Preço:** valor total aplicado àquela faixa.

Ao criar mais de uma regra:

- use valores a partir de uma categoria;
- não sobreponha faixas;
- mantenha o máximo igual ou maior que o mínimo;
- deixe uma regra ilimitada sempre por último;
- informe um preço maior que zero em todas as regras.

Exemplo fictício de faixas válidas:

| Regra | Mínimo | Máximo |
| --- | ---: | ---: |
| Faixa 1 | 2 | 2 |
| Faixa 2 | 3 | 4 |
| Faixa 3 | 5 | Ilimitado |

Os valores não aparecem neste exemplo porque cada organização deve definir sua própria tabela.

## Como o Race Manager calcula o preço

Quando uma inscrição contém várias categorias, o sistema procura a combinação de pacotes que resulte no menor valor possível.

Durante o cálculo:

- uma categoria pode estar vinculada a mais de um pacote;
- cada categoria conta em somente um pacote na mesma inscrição;
- uma regra só é aplicada quando a quantidade está dentro da faixa configurada;
- categorias não cobertas por uma regra aplicável usam o preço unitário;
- o sistema compara as combinações disponíveis e escolhe o menor total.

Por isso, confira tanto as faixas do pacote quanto as categorias vinculadas. Um pacote sem categorias vinculadas não participa do cálculo.

## Escolher a regra de número da moto

A regra é obrigatória ao criar o evento.

| Opção exibida | Efeito operacional |
| --- | --- |
| **Único por categoria** | O mesmo número não pode ser usado por dois pilotos na mesma categoria. A cronometragem fica disponível. |
| **Duplicado sem cronometragem** | Números repetidos são permitidos e a cronometragem fica desabilitada. Os resultados são lançados manualmente. |
| **Duplicado com adesivo colorido** | Números repetidos são permitidos e a cronometragem fica disponível. Pilotos com número repetido precisam ser diferenciados por adesivo colorido; um deles pode permanecer sem adesivo. |

Categorias diferentes podem ter o mesmo número no modo **Único por categoria**. Se essas categorias forem mescladas na mesma bateria, o Race Manager verifica se a identificação continuará sem conflito antes de concluir a mesclagem.

### Alterar a regra depois das inscrições

Prefira definir essa regra antes de cadastrar pilotos. Uma alteração posterior pode ser bloqueada:

- qualquer resultado já enviado impede a troca;
- a mudança para **Único por categoria** exige a correção de números repetidos nas inscrições ativas;
- baterias mescladas também são verificadas;
- inscrições canceladas não entram nessa validação;
- ao concluir a mudança para **Único por categoria**, os adesivos das inscrições ativas são removidos.

Se o sistema apresentar conflitos, corrija as inscrições indicadas e tente salvar novamente. A regra anterior permanece ativa quando a alteração é recusada.

## Configurar a pontuação

A pontuação é configurada depois que o evento foi salvo e ativado.

1. No início do organizador, abra **Regras de Pontuação**. A mesma opção também aparece ao editar um evento já salvo.
2. Use **Adicionar Posição** para criar as colocações necessárias.
3. Informe a quantidade de pontos de cada posição. O valor pode ser zero ou maior.
4. Se o evento usar HoleShot, ative a opção e informe um bônus maior que zero.
5. Selecione **Salvar Regras**.

É necessário cadastrar pelo menos uma posição. As posições são organizadas em sequência e as regras são usadas na classificação do evento e da Copa.

### HoleShot

Quando habilitado, o HoleShot concede o bônus configurado ao piloto indicado no resultado. A atribuição é feita por categoria, inclusive quando duas categorias correm na mesma bateria.

A seleção do vencedor e as regras de elegibilidade serão detalhadas no capítulo operacional de HoleShot.

### Alterar pontos depois de publicar resultados

Em um evento ativo, a alteração das regras recalcula a pontuação dos resultados já publicados. Isso pode mudar a classificação do evento e da Copa.

Antes de salvar uma alteração nessa situação:

1. confirme a nova tabela com a organização;
2. verifique o bônus de HoleShot;
3. salve as regras;
4. revise as classificações e os relatórios afetados.

Em evento histórico com resultados, as regras ficam disponíveis somente para consulta.

## Ordem recomendada de preparação

1. Cadastre as categorias e seus preços unitários.
2. Cadastre os pacotes e vincule as categorias corretas.
3. [Crie o evento](criar-e-configurar-evento.md) e selecione suas categorias.
4. Escolha a regra de número da moto.
5. Salve e ative o evento.
6. Configure a pontuação e o HoleShot.
7. Revise tudo antes de iniciar as inscrições.
