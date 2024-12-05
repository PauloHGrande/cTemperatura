# Projeto conversão de temperatura

### Sobre o projeto
O projeto conversão de temperatura é um projeto desenvolvido em NodeJS. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando NodeJS.

### Observações do projeto
A aplicação é exposta usando a porta 8080

### docker Comando
criado o dockerfile e executar o comando dentro do src pra gerar a imagem a partir do dockerfile
docker build -t pauloggrande/c-temperatura:v1 .
docker container run -d -p 8080:8080 pauloggrande/c-temperatura:v1
