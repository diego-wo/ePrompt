# ePrompt - Trabalho de Conclusão

Este projeto foi desenvolvido como trabalho final para a disciplina de **ePrompt - UFG**.

## Objetivo
O sistema tem como objetivo auxiliar na destinação correta de embalagens de defensivos agrícolas, de acordo com a Lei nº 14.785, de 27 de dezembro de 2023. Utiliza LLMs integrados ao Guardrails para validação e orientação.

## Funcionalidades
- Recebe informações do usuário sobre o tipo de embalagem, se é lavável e se contém resíduos perigosos.
- Valida os dados e fornece orientações baseadas na legislação vigente.
- Implementa controle de qualidade nas respostas utilizando a biblioteca Guardrails.

## Requisitos
- **Python 3.9+**
- Bibliotecas:
  - `dotenv`
  - `pydantic`
  - `guardrails`
  - `uv`

## Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/diego-wo/ePrompt.git
   cd ePrompt
