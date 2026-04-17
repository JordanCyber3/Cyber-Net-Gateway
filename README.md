# ⚡ CYBER-NET GATEWAY v2.0 ⚡
> **Status**: OPERACIONAL | **Codename**: Cyber-Shadow

API de Autenticação Restrita desenvolvida com **FastAPI** e **JWT (JSON Web Tokens)**. Este sistema simula um terminal de acesso seguro com interface personalizada.

## 🚀 Console de Operações
Para testar os protocolos em tempo real, acesse o terminal oficial no Render:

[![Acessar Terminal](https://img.shields.io/badge/Acessar_Terminal-CYBER--NET-0000ff?style=for-the-badge&logo=render&logoColor=white)](https://fastapi-jwt-auth.onrender.com/docs)

---

## 🛠️ Tecnologias Utilizadas
* **Python 3.10+**: Linguagem base do sistema.
* **FastAPI**: Framework de alta performance para a API.
* **JWT**: Segurança baseada em tokens criptografados.
* **Uvicorn**: Servidor ASGI utilizado no deploy.

## 🔓 Protocolos de Acesso
1. **Registro**: Crie sua identidade digital em `/user/signup`.
2. **Extração**: Obtenha sua chave de acesso em `/user/login`.
3. **Bypass**: Insira o token no botão **Authorize** do Swagger.

## 💻 Configuração do Ambiente Local
Siga estes comandos para clonar e rodar o mainframe em sua máquina:

```bash
# 1. Clone o repositório
git clone https://github.com/JordanCyber3/Cyber-Net-Gateway.git

# 2. Instale as dependências
pip install -r requirements.txt

# 3. Inicie o sistema
python main.py
