# api-pokemon

Uma aplicação web desenvolvida para gerenciar times de pokemons de forma simples e rápida.]

## Tecnologias Usadas

Lista das ferramentas e tecnologias principais utilizadas no desenvolvimento:
- [Node.js](https://nodejs.org)
- [TypeScript](https://typescriptlang.org)
- [Express](https://expressjs.com)
- [EJS](https://ejs.co)

## Estrutura de Pastas

```text
seu-projeto/
│
├── src/
│   ├── config/          # Configurações do banco de dados/aplicação
│   ├── controllers/     # Lógica das requisições
│   ├── models/          # Definição dos dados e banco de dados
│   ├── routes/          # Definição das rotas da API
│   ├── views/           # Páginas renderizadas (EJS)
│   └── server.js        # Ponto de entrada da aplicação
│
├── .env.example         # Variáveis de ambiente de exemplo
├── package.json         # Dependências do projeto
└── README.md            # Documentação
```

## Como Executar

Siga o passo a passo abaixo para rodar o projeto na sua máquina local:

### Pré-requisitos
Certifique-se de ter instalado em seu computador:
- [Git](https://git-scm.com)
- [Node.js](https://nodejs.org)

### Passo a Passo

1. **Clone o repositório:**
   Abra seu terminal e digite:
   ```bash
   git clone https://github.com
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd time-pokemon
   ```

3. **Instale as dependências:**
   ```bash
   npm install
   ```

4. **Configure as variáveis de ambiente:**
   Duplique o arquivo `.env.example` para um novo arquivo chamado `.env` e preencha as configurações necessárias.

5. **Execute o projeto:**
   ```bash
   npm run dev
   ```

6. **Acesse a aplicação:**
   Abra seu navegador e acesse: `http://localhost:3000` (ou a porta definida no seu `.env`).

## Endpoints / Rotas

Abaixo estão as rotas disponíveis na API:


| Método | URL | Descrição |
| :--- | :--- | :--- |
| `GET` | `/` | Retorna a página inicial (Home). |
| `GET` | `/api/usuarios` | Retorna a lista com todos os usuários cadastrados. |
| `POST` | `/api/usuarios` | Cria um novo usuário com os dados enviados no corpo. |
| `DELETE` | `/api/usuarios/:id` | Remove o usuário correspondente ao ID especificado. |

## Autor

Desenvolvido por:
- **Heitor Jorge Marques Santos**
- **Turma:** 2° A
- **Instituição:** Senac RN
