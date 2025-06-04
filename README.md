# 🧠 Projeto: Automação de Cadastro de Produtos com Python

Este projeto utiliza **Python** para automatizar o preenchimento de um formulário web com base nos dados de um arquivo `.csv`. A automação é feita usando controle de teclado e mouse para simular o comportamento humano.

## 🚀 Tecnologias Utilizadas

- `pyautogui` – automação de teclado e mouse
- `pandas` – manipulação de dados em planilhas CSV
- `time` – controle de tempo de execução

## ⚙️ Funcionalidades do Script

- Abre o navegador Microsoft Edge via comando do Windows.
- Acessa a URL de login do sistema de cadastro de produtos.
- Realiza login automático.
- Lê os dados de um arquivo `produtos.csv`.
- Preenche os campos do formulário com os seguintes dados:
  - Código
  - Marca
  - Tipo
  - Categoria
  - Preço unitário
  - Custo
  - Observações (se houver)
- Envia os dados e rola a tela para o próximo cadastro.

## 📂 Pré-requisitos

- Python 3 instalado
- Instale as dependências com:
  ```bash
  pip install pyautogui pandas
