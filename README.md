# Rastreador de Preços Automatizado 🛒📈

Este projeto é uma ferramenta para rastreamento automático de preços de produtos na internet. Ele simula a navegação em sites, coleta informações de preços e exibe esses dados em uma interface web.

Atualmente, o rastreador está configurado para o site **Amazon Canadá (amazon.ca)**, mas pode ser adaptado para outros sites de e-commerce.

## 🔥 Tecnologias Utilizadas

- **Backend:** Python + Flask
- **Frontend:** React
- **Automação de Navegação:** Playwright
- **Scraping de Dados:** Bright Data Scraping Browser

## 🚀 Como Rodar o Projeto

### 1. Instalação dos Programas Necessários
- Instale o [Python](https://www.python.org/downloads/).
- Instale o [Node.js](https://nodejs.org/).

### 2. Configurar o Backend (Python + Flask)

No terminal:

```bash
cd backend
pip install -r requirements.txt
playwright install
python app.py

