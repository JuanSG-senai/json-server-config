# json-server-config

* Ter o node instalado na máquina
* Rodar o comando: 'npm init -y'
* Instalar o json-server: 'npm install json-server'

## Criar a API fake

* Comando: 'npx json-server --watch database.json'

### Obs.:

Toda vez que nós alterarmos o arquivo database.json manualmente, teremos que parar o comando no terminal e rodar novamente.

EX: Rode o comando: 'CRTL + c', para parar o terminal, e depois rode novamente o comando: 'npx json-server --watch database.json'.

* Adicionar o arquivo .gitignore para adicionar a pasta node_modules.

Ex.: No arquivo .gitignore, digite: 'node_modules/'.