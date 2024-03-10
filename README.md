# Github Favorites

<p align="center">
  <img alt="Print" src="./print1.png" width="50%">
</p>

O Github Favorites é uma aplicação web que permite aos usuários buscar perfis do GitHub e salvá-los em uma lista de favoritos. A interface intuitiva facilita a adição e remoção de usuários favoritos, bem como a visualização de informações-chave, como o número de repositórios e seguidores.

## Funcionalidades

- Busca de usuários do GitHub pelo nome de usuário.
- Adição de usuários a uma lista de favoritos.
- Armazenamento dos favoritos no `localStorage`.
- Exibição de informações detalhadas dos usuários, como número de repositórios e seguidores.
- Remoção de usuários da lista de favoritos.

## Tecnologias Utilizadas

- HTML
- CSS
- JavaScript
- Fetch API para chamadas HTTP
- `localStorage` para armazenamento local

## Estrutura do Projeto

- `index.html`: Página inicial da aplicação.
- `style.css`: Estilos da aplicação.
- `main.js`: Inicializa a visualização dos favoritos.
- `GithubUser.js`: Classe responsável pela busca de dados dos usuários do GitHub.
- `Favorites.js`: Contém as classes `Favorites` e `FavoritesView` que gerenciam a lógica de dados e a visualização/interface respectivamente.

## Uso

Para adicionar um usuário aos favoritos:

1. Digite o nome de usuário do GitHub no campo de busca.
2. Pressione o botão de adição.
3. O usuário será adicionado à lista de favoritos, caso exista.

Para remover um usuário dos favoritos:

1. Clique no botão de remoção (ícone de x) ao lado do usuário desejado.
2. Confirme a remoção.

## Projeto finalizado
- (https://devgentil.github.io/GithubFavorite/)

## Licença
Este projeto é licenciado sob a Rocketseat, o que significa que você pode usá-lo livremente para fins pessoais e comerciais, mas deve manter o reconhecimento do autor original.

Feito com ❤️ por [DevGentil](https://github.com/DevGentil).
