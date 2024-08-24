# My Anime List
Este é o repositório do projeto **My Anime List**, desenvolvido como parte do trabalho final da disciplina de Programação Web. O projeto foi criado utilizando Angular e Firebase e consome a API do Jikan (MyAnimeList) para permitir que os usuários criem e gerenciem suas listas personalizadas de animes e mangás.

---

## Descrição do Projeto

O **My Anime List** permite que os usuários autentiquem-se no sistema, consumam dados da API do Jikan para buscar animes e mangás, e gerenciem suas listas personalizadas. Os usuários podem adicionar novos títulos à lista, atualizar o status (por exemplo, marcar como "assistido" ou "em andamento"), e remover itens conforme necessário.

---

## Funcionalidades

- **Autenticação de Usuários**:
  - Login e criação de contas utilizando Firebase Authentication (email/senha).

- **Consumo da API do Jikan**:
  - Integração com a API do Jikan para busca e exibição de informações sobre animes e mangás.

- **CRUD de Animes/Mangás**:
  - Permite que os usuários adicionem, editem, atualizem e removam itens da sua lista de animes e mangás.

- **Proteção de Rotas**:
  - Implementação de guards para garantir que apenas usuários autenticados possam acessar certas áreas da aplicação.

- **Pipe Personalizado**:
  - Criação de um Pipe para transformar os títulos dos animes/mangás na exibição.

---

## Requisitos

- Node.js
- Angular CLI
- Firebase

---

## Como Rodar o Projeto

1. **Clone o Repositório**

   ```bash
   git clone https://github.com/Azogh/my-anime-list.git
