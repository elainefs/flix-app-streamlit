# Flix App

## 📘 Sobre

Essa aplicação foi construída com [Streamlit](https://streamlit.io/) para mostrar dados sobre filmes consumidos de [django-flix-api](https://github.com/elainefs/django-flix-api).

Para que essa aplicação funcione corretamente é necessário que a API da qual os dados estão sendo consumidos esteja em execução. Através da API você poderá criar seu usuário e senha para acesso.

Acesse [django-flix-api](https://github.com/elainefs/django-flix-api) para saber como executar a API localmente.

## 💻️ Tecnologias

- Python
- Streamlit

## ⚙️ Instalação e execução

Para executar essa aplicação, siga os seguintes passos:

1. Clone o repositório

```bash
git clone git@github.com:elainefs/flix-app-streamlit.git

cd flix-app-streamlit
```

2. Crie e ative um ambiente virtual

```bash
python3 -m venv .venv # Para Windows use: python -m venv .venv
source .venv/bin/activate  # Para Windows use: .venv\Scripts\activate
```

3. Instale as dependências do projeto

```bash
pip install -r requirements.txt
```

4. Execute a aplicação

```bash
streamlit run app.py
```

A aplicação estará disponível em `http://localhost:8501`.

## 📄 Licença

Este projeto está sobre a licença MIT. Veja o arquivo [LICENSE](https://github.com/elainefs/flix-app-streamlit/blob/main/LICENSE) para mais informações.

---

Made with ❤️ by [Elaine Ferreira](https://github.com/elainefs)
