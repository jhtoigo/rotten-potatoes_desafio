# rotten-potatoes

## Instruções para rodar o projeto

1. Criar arquivo .env baseado no arquivo .env_example.
  
  
2. Rodar o docker-compose para subir os containers
    ```
    docker-compose up -d
    ```
3. Para acessar a aplicação através do navegador utilize a porta definida no .env em WEBPORT:
   
   http://localhost:8083

4. Para parar os containers e removelos utilize o:
    ```
    docker container down
    ```

## Configuração

MONGODB_DB => Nome do database

MONGODB_HOST => Host do MongoDB

MONGODB_PORT => Posta de acesso ao MongoDB

MONGODB_USERNAME => Usuário do MongoDB

MONGODB_PASSWORD => Senha do MongoDB
