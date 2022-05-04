# rotten-potatoes

## Instruções para rodar o projeto

1. Criar arquivo .env baseado no arquivo .env_example.
  - Observação: foi adicionado no projeto o pacote dotenv para o python utilizar também o arquivo .env
  
2. Acessar a pasta src e rodar o docker-compose para subir o mongo e o python
    ```
    cd src/
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
