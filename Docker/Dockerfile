#Usar o node com o Apline como imagem base
FROM node:alpine
#Copiar os arquivos da raiz da aplicação(.) para dentro da pasta /app no container
COPY . /app
#Definir a pasta /app como diretório de trabalho(para não precisar ficar digitando o caminho completo toda hora)
WORKDIR /app
#Executar o comando "node app.js" para executar a aplicação
CMD node app.js