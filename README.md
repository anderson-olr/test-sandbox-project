# test-sandbox-project

Repositório **descartável** para testes locais do Kardume (integração GitHub:
webhooks, vínculos de commits/PRs, execuções de Actions e releases).

- `ci.yml` roda em todo push e manualmente (`workflow_dispatch`, campo `fail`
  para forçar falha sob demanda).
- Releases e tags criadas aqui são apenas de teste (ex.: `v0.0.1-test`).
