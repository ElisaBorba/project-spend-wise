# 🪙 SpendWise

Este projeto consiste em uma aplicação desenvolvida utilizando **React** e **Redux**, que permite aos usuários computar gastos em diferentes moedas e convertê-los para uma moeda única escolhida pelo usuário.
A aplicação acessa um endpoint da API de Cotações de Moedas para obter informações sobre nomes, cotações e outros dados sobre as moedas.

## ⚙️ Funcionalidades
* Adicionar, remover e editar um gasto.

* Visualizar uma tabela de gastos.

* Converter o total de gastos para uma moeda escolhida pelo usuário.

## 🛠 Tecnologias utilizadas

* [React](https://reactjs.org/) - Biblioteca JavaScript/TypeScript para construção da interface do usuário.
* [Redux](https://redux.js.org/) - Gerenciador de estado para aplicações JavaScript/TypeScript.
* [Vitest](https://vitest.dev/) - Framework de teste para aplicações React.
* [Jest](https://jestjs.io/) - Framework de testes.
* [Testing Library](https://testing-library.com/) - Conjunto de ferramentas para testes de componentes React.
* [TypeScript](https://www.typescriptlang.org/)
* CSS Modules
* API de Cotações de Moedas:
  
A aplicação utiliza uma [API de Cotações](https://economia.awesomeapi.com.br/json/all) de Moedas para obter informações sobre as moedas. Esta API fornece dados atualizados sobre diversas moedas, incluindo nome, código, valor de compra e venda, variação, entre outros.

### Estrutura do projeto
```
.
├── src/
│   ├── components/
│   │   ├── Header.tsx
│   │   ├── Table.tsx
│   │   └── WalletForm.tsx
│   ├── pages/
│   │   ├── Login.tsx
│   │   └── Wallet.tsx
│   ├── redux/
│   │   ├── actions/
│   │   ├── reducers/
│   │   └── index.ts     (store)
│   ├── services/
│   │   └── currenciesAPI.ts
│   ├── tests/
│   │   ├── mockData.ts
│   │   ├── renderWith.tsx
│   │   └── requisitoTestes.test.tsx
│   ├── App.tsx
│   └── main.tsx
│   └── types.ts
├── README.md
└── package.json
```

### ▶️ Como executar

1️⃣ Instale as dependências:
```
npm install
```
2️⃣ Inicie a aplicação:

```
npm run dev
```
