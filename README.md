# local-terraform

> Toda infra => Terraform

# 1 - PASSO

## Subir o LocalStack

```
localstack status -d
```

# 2 - PAASO

```
## instalar o tflocal
pipx install terraform-local
cd terraform
tflocal plan
tflocal apply
```

ou

```
npm run infra:init
npm run infra:apply

```

## 02 Subir as funções lambdas via Serverless Framweworks

```
npm run deploy
```
