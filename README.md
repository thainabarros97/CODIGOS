# 🤖 Automação de Indicadores de Vendas

## 📌 Sobre o projeto

Este projeto foi desenvolvido em Python com o objetivo de automatizar um processo de análise de vendas.

A automação realiza o acesso a uma base de dados, coleta informações de vendas, calcula indicadores importantes e envia um relatório automaticamente por e-mail.

## 🎯 Objetivo

Reduzir atividades manuais e agilizar a geração de indicadores de vendas, diminuindo o tempo gasto em tarefas repetitivas.

## ⚙️ Funcionalidades

- Acesso automático ao sistema utilizando PyAutoGUI;
- Download da base de dados de vendas;
- Leitura e análise da planilha Excel;
- Cálculo dos indicadores:
  - Faturamento total;
  - Quantidade de produtos vendidos;
- Geração automática de relatório;
- Envio do relatório por e-mail.

## 🛠️ Tecnologias utilizadas

- Python
- PyAutoGUI
- Pandas
- Excel
- Pyperclip
- Visual Studio Code

## 📂 Estrutura do projeto
📁 Automacao-Indicadores
│
├── codigo.py
├── Análise de Dados - Inicial.ipynb
└── README.md

## 📊 Indicadores calculados

O projeto realiza o cálculo de:

**Faturamento total**
- Soma dos valores finais das vendas.

**Quantidade de produtos vendidos**
- Soma da quantidade de produtos comercializados.

## 🚀 Como executar o projeto

1. Instalar as bibliotecas necessárias:

```bash
pip install pyautogui pandas openpyxl pyperclip
