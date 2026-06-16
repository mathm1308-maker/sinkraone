# Sinkra One Workspace

Este repositorio organiza o site principal da Sinkra One, sites de clientes, dados, documentos e referencias de trabalho.

## Estrutura

- `sites/sinkra-one/site-principal/`: site oficial da Sinkra One.
- `sites/clientes/`: projetos de sites e materiais de outras empresas.
- `sites/clientes/_modelo-cliente/`: modelo de pasta para iniciar um novo cliente.
- `dados/`: dados gerais do negocio, separados em brutos, processados e exportacoes.
- `documentacao/`: processos, propostas, contratos e documentos internos.
- `referencias/`: marcas, layouts, imagens e materiais de inspiracao.
- `inbox/`: entrada temporaria para arquivos novos antes de organizar.

## Padrao para novos clientes

Crie uma pasta em `sites/clientes/nome-do-cliente/` com esta base:

```text
site/
dados/
documentos/
referencias/
```

Use nomes em minusculo, sem espacos e com hifens. Exemplo: `academia-mestre-sandro`.

## Sites atuais

- Sinkra One: `sites/sinkra-one/site-principal/index.html`
- Academia Mestre Sandro: `sites/clientes/academia-mestre-sandro/site/index.html`
