# Angular GH Pages

Instale o angular-cli-ghpages

    npm i -g angular-cli-ghpages
    
Rode o build do Angular

    ng build --prod --base-href "https://USERNAME.github.io/REPOSITORY_NAME/"
    
Exemplo:

    ng build --prod --base-href "https://gabrielferreir.github.io/angular-ghpages/"
    
Após o build ser finalizado rode o comando abaixo:

OBS:. Ele faz com que o angular-cli-ghpages crie um novo branch e suba somente os arquivos de build necessarios para o Github Pages

    ngh
    
Documentação oficial: https://www.npmjs.com/package/angular-cli-ghpages
