
# Flix

Flix é uma aplicação web para streaming de filmes e séries. Ela está sendo desenvolvida como parte de um curso na Pragmatic Studio


## Instalação

Para executar a aplicação Flix localmente, você precisará ter o Ruby, o Ruby on Rails e o PostgreSQL instalados em sua máquina. Você pode seguir as instruções de instalação para o seu sistema operacional no site oficial do Ruby on Rails: https://rubyonrails.org/

```bash
  git clone git@github.com:matheusmoura0/Flix-Rails.git
  cd flix
  bundle install
```
Em seguida, você precisará configurar o banco de dados executando os seguintes comandos:

```bash
  rails db:create
  rails db:migrate
  rails db:seed
```
Por fim, você pode iniciar o servidor Rails executando o seguinte comando:

```bash
  rails server
```
Você agora deve ser capaz de acessar a aplicação Flix navegando para http://localhost:3000/ em seu navegador da web

## Uso

Depois de ter a aplicação Flix em execução, você pode usá-la para navegar e fazer streaming de filmes e séries. Você pode criar uma conta para salvar seus títulos favoritos, avaliar títulos e deixar comentários. Você também pode pesquisar títulos por título, diretor ou ator.


## Contribuindo

Se você gostaria de contribuir para o projeto Flix, siga o fluxo de trabalho padrão do GitHub:

Faça um fork do repositório
Clone o repositório bifurcado para sua máquina local
Crie um novo branch para suas alterações
Faça suas alterações e as confirme no novo branch
Envie o branch para o repositório bifurcado
Crie um pull request para mesclar as alterações no repositório principal