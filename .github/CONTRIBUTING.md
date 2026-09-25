# Como contribuir — Plathion

Obrigado por contribuir com um repositório da Plathion. Este guia define o fluxo padrão que seguimos em todos os projetos da organização.

## Ambiente de desenvolvimento

Use o ambiente padronizado da empresa: [`dev-platform-d13`](https://github.com/plathiontecnologia/dev-platform-d13) (Debian 13 + Docker/dev containers). Isso garante que todo mundo desenvolve nas mesmas condições, evitando o clássico "na minha máquina funciona".

## Branches

- `main` — sempre estável, protegida contra push direto.
- `feature/nome-da-feature` — novas funcionalidades.
- `fix/nome-do-bug` — correções de bug.
- `chore/descricao` — manutenção, dependências, configuração.

## Commits

Seguimos o padrão [Conventional Commits](https://www.conventionalcommits.org/pt-br/):

```
feat: adiciona autenticação via WhatsApp
fix: corrige cálculo de estoque no relatório de BI
docs: atualiza README do módulo de infraestrutura
refactor: reorganiza camada de serviços
chore: atualiza dependências
```

## Pull Requests

1. Abra a branch a partir da `main` atualizada.
2. Faça commits pequenos e descritivos.
3. Abra o Pull Request preenchendo o template.
4. Garanta que os checks automáticos (lint, testes) passam antes de pedir revisão.
5. Merge por **squash**, mantendo o histórico da `main` limpo.

## Dúvidas

Fale com **diretoria@plathion.com**.
