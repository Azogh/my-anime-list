# My Anime List

## Descrição

"My Anime List" é uma aplicação web desenvolvida em Angular que permite aos usuários criar e gerenciar uma lista personalizada de animes e mangás que estão acompanhando. Os usuários podem adicionar novos títulos, atualizar o status (por exemplo, marcar como "assistido" ou "em andamento"), e remover itens da lista.

Este projeto foi criado como parte do trabalho final da disciplina de Programação Web no curso de Sistemas de Informação.

## Funcionalidades

- **Autenticação de Usuários**: O sistema permite que os usuários façam login e criem novas contas utilizando o Firebase Authentication.
- **CRUD de Animes/Mangás**: Os usuários podem adicionar, editar, e remover animes e mangás da sua lista personalizada.
- **Consumo da Jikan API**: A aplicação consome dados da Jikan API para fornecer informações detalhadas sobre os animes e mangás.
- **Proteção de Rotas**: Algumas rotas são protegidas, garantindo que apenas usuários autenticados possam acessar certas áreas do sistema.
- **Pipeline Personalizado**: Um pipe personalizado é utilizado para destacar o status dos animes/mangás na lista.
  
## Tecnologias Utilizadas

- Angular
- Firebase Authentication
- Firestore (para armazenamento dos dados)
- Jikan API
- HTML/CSS
- TypeScript

## Pré-requisitos

- Node.js
- Angular CLI

## Instalação

1. Clone este repositório para a sua máquina local:

   ```bash
   git clone [URL do Repositório]
Navegue até o diretório do projeto:

bash
Copiar código
cd my-anime-list
Instale as dependências:

bash
Copiar código
npm install
Comandos Disponíveis
Compilar e recarregar automaticamente para desenvolvimento:

bash
Copiar código
npm run serve
Hospedar no GitHub Pages:

bash
Copiar código
npm run deploy
API
Este projeto utiliza a Jikan API para obter dados sobre animes e mangás.

Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.
