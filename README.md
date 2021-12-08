# Comunicacao

# 🚀 CISS

O projeto de software CISS visa a construção de  um sistema de agendamento por horário das salas disponíveis para melhor organização do funcionamento do Centro Integrado de Saúde da UniFG. 
Em primeiro momento a aplicação focará na identificação de conflitos de agendamentos nas salas, mas ao decorrer do projeto Sertão in Tech mais funcionalidades serão adicionadas ao sistema.

 # ⚠️ Pré-requisitos 

* Instalar o NODE.JS.  

* Instalar o POSTMAN.

* Instalar o GIT.

# ⚙️ Instalação


  REMOVER

    $ sudo apt remove cmdtest

    $ sudo apt remove yarn

INSTALAR

    $ curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -

    $ echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.$ list.d/yarn.list

    $ sudo apt-get update

    $ sudo apt-get install yarn -y

    $ yarn install

## Instalando o npm linux

REMOVER

    $ sudo apt remove npm

INSTALAR

    $ sudo apt install npm

## Comando do fio:

INSTALAR PACOTE

    $ yarn add {nome do pacote}

INICIAR PROJETO

    $ yarn init -y

INSTALAR NODE_MODULES

    $ yarn add yarn
## Comando do npm:

INSTALAR PACOTE

    $ npm install {nome do pacote}

INICIAR PROJETO

    $ npm init -y

INSTALAR LIB DO PROJETO NODE_MODULES

    $ npm install

## Manipulando DB Migration sequelise com yarn

 PARA CRIAR DATABASE:

    $ yarn sequelize db:create

PARA CRIAR UMA ARQUIVO DE MIGRATION:

    $ yarn sequelize migration:create --name=c{nome que deseja colocar}

COLOCAR AS MIGRATION EM PRODUÇÃO:

    $ yarn sequelize db:migrate
    
Sequência de migração Manipulando DB com npm

INSTALAR sequelize-cli

    $ npm install --save-dev sequelize-cli

PARA CRIAR DATABASE:

    $ npm sequelize db:create {obs: para SGDB sqlite não precisa rodar esse comando}

PARA CRIAR UMA ARQUIVO DE MIGRATION:

    $ npm sequelize migration:create --name={nome que deseja colocar}

COLOCAR AS MIGRATION EM PRODUÇÃO:

    $ npx sequelize db:migrate {obs: esse comando para SGDB sqlite, já cria o DB automaticamente}

## Alguns comandos de debbug no linux

FINALIZAR O SERVIÇO QUE USA UMA PORTA

    $ sudo killall -9 node

 SABER QUAL SERVIÇO ESTA USANDO UMA PORTA

    $ sudo lsof -i :{número da porta a consultar
## 💡 End points 

END POINTS DA API SERTÃO IN TECH

* TODAS AS ROTAS SÓ PODERÃO SER ACESSADAS ATRAVÉS DE UM TOKEN QUE É GERADO APOS O LOGIN DO USUÁRIO.

### ROTAS DE LOGIN DO USUÁRIO:

    HTTP://dominio/users > METODO DE VERBO GET;

    HTTP://dominio/users > METODO DE VERBO POST;

    HTTP://dominio/users/:USER_ID > METODO DE VERBO PUT;

    HTTP://dominio/users/:USER_ID > METODO DE VERBO DELETE;

    HTTP://dominio/users/login > METODO DE VERBO POST;

### ROTAS DA SALA:

    HTTP://dominio/space > METODO DE VERBO GET;

    HTTP://dominio/space > METODO DE VERBO POST;

    HTTP://dominio/space/:sala_id > METODO DE VERBO PUT;

    HTTP://dominio/space/:sala_id > METODO DE VERBO DELETE;

### ROTAS DA MATERIA/DISCIPLINA:

    HTTP://dominio/discipline > METODO DE VERBO GET;

    HTTP://dominio/discipline > METODO DE VERBO POST;

    HTTP://dominio/discipline/:discipline_id > METODO DE VERBO PUT;

    HTTP://dominio/discipline/:discipline_id > METODO DE VERBO DELETE;

###  ROTAS DO CONTATO:

    HTTP://dominio/contacts > METODO DE VERBO GET;

    HTTP://dominio/contacts > METODO DE VERBO POST;

    HTTP://dominio/contacts/:contacts_id > METODO DE VERBO PUT;
    
    HTTP://dominio/contacts/:contacts_id > METODO DE VERBO DELETE;


### RETAS DO RPOFESSOR:

    HTTP://dominio/teachers > METODO DO VERBO GET
    

    HTTP://dominio/teachers > METODO DO VERBO POST;

    HTTP://dominio/teachers/:teacher_id METODO DE VERBO PUT;

    HTTP://dominio/teachers/:teacher_id METODO DE VERBO DELETE;

### ROTA DO ARQUIVO EM LOTE XLSX:

    HTTP://dominio/upload > METODO DO VERBO POST;
## 🛠️ Construído com

* HEROKU - Serviço de PaS ultilizado 
* JAVASCRIPT- Linguagem de Programação ultilizado
* API com NODE.JS

##  ❗ Versão
 Sem versão disponivel.
## 🔥 Autores

- [Gabriele Cardoso](https://github.com/2433461)
- [Matheus Gama](https://github.com/MatheusGama01)
- [Marco Alexandre]()
- [Tiago Teixeira]()
- [Andre Nogueira]()
- [José Victor]()

 ## 😊  Orientadores 
 
- [Raissa Arruda]()
- [Hissamu Shirado]()


