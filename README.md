Json Server

O processo é bem simples e para teste eu utilizei o Postman. 

Primeiro passo é instalar o Json Server:
npm install –g json-server

E logo em seguida dar um:
npm init (para criar o arquivo package.json)

Segundo passo é criar um arquivo db.json e depois inicializar o servidor com o comando:

json-server –watch db.json –port 3001 

Nota-se que eu mudei o número padrão da porta. Foi feito para não dar conflito com a porta do React, que por padrão, também é na porta 3000.
