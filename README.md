# Eplay - E-commerce de Games 🎮

Este é mais um projeto prático desenvolvido para o bootcamp da EBAC. O objetivo desta aplicação é aplicar conceitos avançados de React, criando um e-commerce de jogos digitais completo e funcional, com foco em integração de APIs, gerenciamento de estado global e estilização componentizada.

### 🚀 Funcionalidades

A aplicação consiste em uma loja virtual completa onde o usuário pode explorar, adicionar ao carrinho e comprar jogos. O fluxo da aplicação abrange as seguintes etapas:

- **Catálogo de Jogos:** Listagem dinâmica de jogos consumidos via API, organizados por categorias (Lançamentos, Promoções, Ação, RPG, etc.).
- **Detalhes do Produto:** Página dedicada para cada jogo, exibindo informações detalhadas, sinopse, galeria de mídias, preço e especificações de sistema.
- **Carrinho de Compras:** Sistema de adição e remoção de jogos, com cálculo automático do valor total da compra.
- **Checkout:** Fluxo de compra por etapas integrando formulários para dados de cobrança, endereço de entrega e informações de pagamento (Boleto ou Cartão de Crédito).
- **Confirmação:** Tela de sucesso gerada após a comunicação com a API, retornando o ID (código) do pedido finalizado.

### 🛠 Tecnologias Utilizadas

O projeto foi construído utilizando as seguintes ferramentas e bibliotecas:

- **React:** Biblioteca principal para a construção da interface de usuário e gerenciamento de rotas (React Router DOM).
- **Redux (Redux Toolkit & RTK Query):** Responsável pelo gerenciamento do estado global do carrinho de compras e pelo consumo eficiente da API REST, lidando com chamadas assíncronas (queries e mutations) e cache.
- **Formik & Yup:** Utilizados em conjunto no fluxo de checkout para construir o formulário, gerenciar seus estados e aplicar validações rigorosas (campos obrigatórios, quantidade de caracteres, etc.) antes do envio dos dados.
- **Styled Components:** Biblioteca de CSS-in-JS utilizada para a estilização isolada e dinâmica dos componentes.
- **TypeScript:** Utilizado para garantir a tipagem estática dos dados recebidos da API (produtos, pedidos) e das propriedades dos componentes, evitando erros em tempo de execução.

### ⚙️ Como executar o projeto na sua máquina

Certifique-se de ter o Node.js instalado. Em seguida, siga o passo a passo abaixo no seu terminal:

1. Clone este repositório:
```bash
# 1. Clone este repositório
git clone [https://github.com/VitorV9/eplay.git](https://github.com/VitorV9/eplay.git)

# 2. Acesse a pasta do projeto
cd eplay

# 3. Instale as dependências
npm install

# 4. Inicie o servidor de desenvolvimento
npm start
