# 🧪 Banco API Tests

Projeto de automação de testes para API REST disponível em:
👉 https://github.com/juliodelimas/banco-api

---

## 📌 Objetivo

Este projeto tem como objetivo automatizar testes da API REST do sistema bancário, validando seus endpoints e contribuindo que as regras de negócio estejam sendo respeitadas.

A automação permite:

* Garantir a qualidade da API
* Detectar regressões rapidamente
* Validar contratos de endpoints
* Apoiar pipelines de CI/CD

---

## 🚀 Stack utilizada

O projeto foi desenvolvido utilizando:

* **JavaScript (Node.js)**
* **Mocha** → Framework de testes
* **Chai** → Biblioteca de asserções
* **Supertest** → Testes de requisições HTTP
* **Mochawesome** → Relatórios em HTML
* **dotenv** → Variáveis de ambiente

---

## 📁 Estrutura do projeto

```bash
banco-api-tests/
│
├── test/                  # Arquivos de testes automatizados
│   ├── usuarios.test.js
│   └── transacoes.test.js
│
├── mochawesome/           # Relatórios HTML gerados após execução
│
├── .env                   # Variáveis de ambiente (deve ser criado)
├── .gitignore
├── package.json
└── README.md
```

---

## ⚙️ Configuração do ambiente

### 1. Clonar o repositório

```bash
git clone https://github.com/0028dani/banco-api-tests.git
cd banco-api-tests
```

### 2. Instalar dependências

```bash
npm install
```

---

## 🔐 Configuração do `.env`

Crie um arquivo `.env` na raiz do projeto com o seguinte conteúdo:

```env
BASE_URL=http://localhost:3000
```

### 📌 Descrição

* `BASE_URL`: URL base da API que será testada
  (ex: ambiente local, homologação ou produção)

⚠️ Certifique-se de que a API esteja rodando antes de executar os testes.

---

## ▶️ Execução dos testes

Para executar todos os testes:

```bash
npm test
```

---

## 📊 Relatórios de teste

O projeto utiliza o **Mochawesome** para geração de relatórios em HTML.

Após a execução dos testes, o relatório será gerado automaticamente no diretório:

```bash
/mochawesome
```

### Como visualizar:

1. Acesse a pasta `mochawesome`
2. Abra o arquivo `.html` no navegador

---

## 📚 Documentação das dependências

* Mocha → https://mochajs.org/
* Chai → https://www.chaijs.com/
* Supertest → https://github.com/ladjs/supertest
* Mochawesome → https://github.com/adamgruber/mochawesome
* dotenv → https://github.com/motdotla/dotenv

---

## 🔗 Projeto testado

API utilizada nos testes:
👉 https://github.com/juliodelimas/banco-api

---


