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

## Demandas e Pull Requests

1. Toda demanda fica no quadro [Plathion · Demandas](https://github.com/orgs/plathiontecnologia/projects/1): o **plano** de um pacote é uma issue, cada **spec** é uma sub-issue; fora de pacote, use os modelos **Defeito** ou **Ajuste**.
2. Abra a branch a partir da `main` atualizada (`feat/`, `fix/`, `docs/`, `chore/`).
3. Um commit por entrega, com a mensagem já no formato do modelo de PR (Resumo, O que entra, Decisões e base, Como conferir): com um commit só, o GitHub preenche o PR sozinho.
4. O PR fecha a demanda com `Closes #N` e só vai para revisão com os checks automáticos verdes.
5. O merge é sempre feito pelo Helder.

## Dúvidas

Fale com **diretoria@plathion.com**.
