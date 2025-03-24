# 🤖 Chatbot para E-Commerce

## 📝 Descrição

Este projeto consiste em um chatbot construído a partir da API do Gemini. Seu objetivo é servir somo um assistente, responder a dúvidas de clientes e assumir diferentes comportamentos de acordo com o temperamento do cliente. Para exemplificar, foi escolhido um negócio de calçados chamado <strong style='color:red;'>ShoetopIA</strong>.

## 🧩 Tecnologias

|    |                | 
|----|----------------|
| 🧩 | **Python**     | 
| 🧩 | **Gemini API** | 
| 🧩 | **Flask**      | 
| 🧩 | **HTML**       |
| 🧩 | **CSS**        |
| 🧩 | **JavaScript** | 
---

## 🛠️ Configuração do Ambiente

Após baixar o projeto e abrir com a IDE de sua preferência, é necessário criar um ambiente virtual (venv) para isolar as dependências do projeto em relação ao sistema operacional:

### venv no Windows:

```bash
python -m venv .venv
source .venv/Scripts/activate
```

### venv no Mac/Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
```
Em seguida, instale os pacotes utilizando:

```bash
pip install -r requirements.txt
```

## 🔑 Gerar API_KEY e associar ao .env

Crie um arquivo .env na raíz do projeto, pois por padrão ele não é versionado.
```python
GEMINI_API_KEY = "SUA_CHAVE_AQUI"
```

## 🚀 Rodando o projeto

Execute `python app.py`

Pesquise no navegador por `http://127.0.0.1:5000`

Para interromper a execução, tecle `Ctrl + C` no terminal.