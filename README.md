# Rocketseat - Desafio: GoRestaurant Mobile

## Sobre o desafio

Desenvolvimento da aplicação GoRestaurant versão Mobile. Focando na prática do React Native juntamente do TypeScript, para criar um pequeno app para pedidos de comida.

Essa será uma aplicação que irá se conectar a uma Fake API, e exibir e filtrar os pratos de comida da API e permitir a criação de novos pedidos.

## Rotas fake API

- /foods: Retorna todas as comidas cadastradas na API
- /foods/:id: Retorna um prato de comida cadastradas na API baseado no id
- /categories: Retorna todas as categorias cadastradas na API
- /orders: Retorna todas os pedidos que foram cadastrados na API
- /favorites: Retorna todas as comidas favoritas que foram cadastrados na API

## Funcionalidades da aplicação

- **Listar os pratos de comida:** A página Dashboard deve ser capaz de exibir uma listagem, com o campo name, value e description de todos os pratos de comida que estão cadastrados na API.

- **Listar as categorias:** A página Dashboard deve ser capaz de exibir uma listagem, com o campo title e image_url de todas as categorias que estão cadastrados na API.

- **Filtrar pratos de comida por busca ou por categorias:** A página Dashboard deve permitir que o input de pesquisa e os botões de categoria façam uma busca na API de acordo com o que estiver selecionado ou escrito no input.

- **Listar os pedidos:** A página Orders deve ser capaz de exibir uma listagem, com o campo as informações do produto pedido, com name e description de todos os pedidos que estão cadastrados na API.

- **Listar os pratos favoritos:** A página Favorites deve ser capaz de exibir uma listagem, com o campo as informações do produto favorito, com name e description de todos os pedidos que estão cadastrados na API.

- **Realizar um pedido:** Na página Dashboard, ao clicar em um item, você deve redirecionar o usuário para a página FoodDetails, onde será possível realizar um novo pedido, podendo controlar a quantidade desse item pedido, ou adicionar ingredientes extras. Todo o valor deve ser calculado de acordo com a quantidade pedida.

## Start
```js
    yarn                                  // instala dependências
    yarn json-server server.json -p 3333  // executa fake API
    yarn android                          // inicia aplicação android
    yarn ios                              // inicia aplicação ios em caso de Mac
    yarn test                             // executa os testes
```
