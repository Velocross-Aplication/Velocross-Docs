# Como contribuir com a documentação

Este repositório é a fonte principal da documentação pública do Race Manager. As alterações são revisadas no GitHub antes da sincronização com o GitBook.

## Fontes de verdade

Antes de documentar uma função:

1. verifique a navegação e o comportamento na versão atual do frontend;
2. consulte os contratos do backend quando uma regra não estiver clara;
3. confira a implementação do backend quando o contrato e o comportamento observado não forem suficientes;
4. registre uma divergência antes de escrever sobre comportamentos incompatíveis.

Não use planos antigos, telas sem acesso pela navegação atual ou código não concluído como prova de que uma função está disponível ao usuário.

## Arquitetura editorial

A documentação deve crescer por fluxo de trabalho, seguindo esta estrutura:

```text
README.md
comecando/
  visao-geral.md
  acesso-e-primeiros-passos.md
  perfis-e-permissoes.md
organizacao-do-evento/
  eventos-ativos-e-historicos.md
  criar-e-configurar-evento.md
  categorias-pacotes-e-regras.md
  equipe-do-evento.md
inscricoes/
  gerenciar-inscricoes.md
  financeiro-da-inscricao.md
dia-da-prova/
  ordem-e-baterias.md
  categorias-mescladas.md
  cronometragem.md
  resultados-manuais.md
  holeshot.md
  narrador.md
resultados-e-relatorios/
  relatorios-do-evento.md
  copa-e-classificacao.md
ajuda/
  duvidas-frequentes.md
  problemas-comuns.md
  suporte.md
referencia/
  mapa-de-funcionalidades.md
assets/images/
```

Arquivos futuros devem ser adicionados ao `SUMMARY.md` somente quando tiverem conteúdo validado. Evite criar uma página pequena para cada botão ou repetir a mesma explicação em vários capítulos.

## Padrão de escrita

- Escreva em português do Brasil.
- Use frases diretas e termos visíveis na interface.
- Explique primeiro o objetivo e depois os passos.
- Numere procedimentos na ordem em que devem ser executados.
- Avise quando uma função depender de perfil, permissão ou configuração.
- Evite nomes de rotas, campos técnicos e detalhes de implementação no manual público.
- Não invente regras para preencher lacunas.

## Privacidade e segurança

Nunca publique:

- CPF, telefone ou e-mail real;
- nome completo de piloto real sem autorização;
- usuário, senha, código de recuperação ou credencial;
- token ou identificador interno real;
- endereço de serviço interno;
- log de produção;
- valor financeiro real de uma organização ou evento.

Use dados fictícios em exemplos, testes e imagens.

## Imagens

Salve imagens em `assets/images`. Use nomes descritivos em letras minúsculas, sem espaços, por exemplo:

```text
assets/images/selecionar-evento.png
```

Antes de adicionar uma captura:

1. prepare dados completamente fictícios;
2. confira todas as áreas visíveis da tela;
3. corte partes que não ajudam no procedimento;
4. adicione texto alternativo claro no Markdown;
5. valide a imagem no GitBook.

## Links e navegação

- Use links relativos entre páginas.
- Mantenha os nomes dos arquivos estáveis depois da publicação.
- Atualize o `SUMMARY.md` ao publicar uma nova página.
- Valide todos os links antes de solicitar revisão.

## Revisão

Uma alteração está pronta para revisão quando:

- o comportamento foi confirmado na versão atual;
- as regras foram conferidas nas fontes de verdade;
- eventuais divergências foram registradas;
- nenhum dado sensível foi incluído;
- os links locais funcionam;
- o `SUMMARY.md` representa a navegação desejada;
- o texto foi lido como instrução para uma pessoa sem conhecimento técnico.
