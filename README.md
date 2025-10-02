# Automacao-GSheets-Discord

Projeto: automação para capturar dados de uma planilha, gerar imagens e enviar para um canal do Discord.

> **Importante:** Este repositório contém apenas o *esqueleto* do projeto — sem credenciais, sem CSVs de produção e sem dados sensíveis.

## Estrutura

- `scripts/` — scripts Python (esqueletos seguros)
- `images/` — pasta vazia para imagens geradas
- `requirements.txt` — pacotes sugeridos
- `.gitignore` — itens para não versionar (credenciais, dados)

## Scripts

- `01_get_data_gsheet.py` → captura os dados da planilha (esqueleto seguro)
- `02_create_image.py` → gera imagem da tabela (esqueleto seguro)
- `03_send_to_discord.py` → envia a imagem para Discord (esqueleto seguro)

## Como usar

1. Clone o repositório
2. Crie um ambiente virtual (recomendado)
3. Instale dependências (ex.: `pip install -r requirements.txt`)
4. Implemente suas credenciais ou dados localmente
5. Execute os scripts na ordem: `01` → `02` → `03`

## Segurança

- **NÃO** coloque `credentials.json`, arquivos `.env` ou CSVs reais no repositório público.
- Para exemplos, crie arquivos fictícios (`example_*.csv`) mostrando a estrutura dos dados sem expor informações reais.
