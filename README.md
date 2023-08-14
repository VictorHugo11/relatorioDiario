# Automatização de Relatório Financeiro: Ibovespa e Dólar 🐍📊📧

Este projeto simples, desenvolvido em Python, automatiza a coleta, análise e envio de relatórios sobre o desempenho diário do Ibovespa e do Dólar. Ele busca os dados, realiza cálculos e gera gráficos para uma análise rápida e eficaz, e envia um relatório detalhado por email.

## Funcionalidades

- Coleta automática de dados do Ibovespa e do Dólar no Yahoo Finance.
- Cálculos de retorno diário, mensal e anual para avaliar o desempenho dos ativos.
- Geração de gráficos intuitivos usando a biblioteca Matplotlib.
- Envio automatizado de relatórios por email, incluindo números e gráficos anexados.

## Pré-Requisitos

- Python 3.x instalado.
- Pacotes: pandas, yfinance, matplotlib, mplcyberpunk, smtplib, email (disponíveis via pip).
- Uma conta de email (Gmail recomendado para facilitar a configuração).

## Como Usar

1. Clone este repositório para o seu sistema local.

2. Instale as bibliotecas necessárias utilizando o comando:

3. Configure o arquivo `.env` com suas credenciais de email.

4. Execute o script `relatorio_diario.py`.

5. Verifique a caixa de entrada do seu email para receber o relatório diário.

## Personalização

- O código pode ser facilmente adaptado para incluir outros ativos financeiros.
- Personalize o formato e o conteúdo do email de acordo com suas preferências.
