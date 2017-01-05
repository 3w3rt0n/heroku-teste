# heroku-teste
Teste básico de deploy no PaaS Heroku, somente os arquivo minimos necesarios para roda uma aplicação Node.JS no Heroku.

São necesarios no minimo 3 arquivos:
1. Procfile - Arquivo que informar ao Heroku qual o arquivo JS responsavel pela inicialização do servidor
Obs.: O nome do arquivo tem de ser exatamente "Procfile" o servidor do Heroku não aceita se for escrito de outra forma como por exemplo: "Procfile.txt", "Procfile.js" e etc.
2. Package.json - Arquivo padrão do Node.JS 
3. index.js - O Node.JS propriamente dito, o nome desse arquivo pode ser qualquer desde que seja especificado no Procfile. 
