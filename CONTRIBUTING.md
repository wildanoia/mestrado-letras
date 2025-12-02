# Guia de Commits (Conventional Commits para LaTeX)

Todos os commits devem seguir o padrão:

<tipo>(escopo opcional): <descrição>

## Tipos principais

- feat → adicionar novo conteúdo (capítulos, seções, apêndices, macros)
  Ex: feat(chapter2): incluir seção sobre limites e continuidade

- fix → corrigir erros de compilação, pacotes ou referências
  Ex: fix(bibliografia): corrigir chave BibTeX duplicada

- docs → atualizar documentação (README, instruções de compilação, comentários)
  Ex: docs(readme): explicar como compilar com XeLaTeX

- style → ajustes de formatação (espaçamento, indentação, fontes)
  Ex: style(tabelas): alinhar colunas corretamente

- refactor → reorganizar ou comentar funcionalidades obsoletas
  Ex: refactor(macros): comentar comando não utilizado no preâmbulo

- chore → manutenção estrutural (criar diretórios, atualizar .gitignore, remover pacotes)
  Ex: chore(structure): adicionar pasta para figuras

- test → adicionar ou corrigir testes de compilação (CI/CD)
  Ex: test(ci): configurar workflow para compilar PDF automaticamente