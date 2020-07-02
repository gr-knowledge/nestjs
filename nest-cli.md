# `NestJS`

## Instalação
```properties
npm i -g @nestjs/cli
```

****

## Help
```properties
nest --help

# Help específico para um comando "generate"
nest generate|g --help
```

****

## Novo Projeto
```properties
nest new|n my-project
```

****

## Converter para Monorepo
```properties
nest generate app my-app
```

****

## Instalação de pacotes
```properties
npm i --save @types/express
npm i --save @nestjs/typeorm typeorm mssql
npm i --save @nestjsx/crud @nestjsx/crud-typeorm
npm i --save class-transformer class-validator

# Todos os comandos numa única linha
npm i --save @types/express @nestjs/typeorm @nestjsx/crud @nestjsx/crud-typeorm typeorm mssql class-transformer class-validator
```

****

## Executar projeto
```properties
npm run start

# Modo desenvolvedor
npm run start:dev

# Rodar projeto específico
npm run start:dev my-app
```

****

## Nest Generate
$ nest g <`schematic`> <`name`> [`options`]

Name | Alias| Description
--|--|--
app | | Nova aplicação monorepo
library | lib | Nova biblioteca
class | cl | Nova classe
controller | co | Novo controller
decorator | d| Novo decorador
filter | f | Novo filtro
gateway | ga | Novo gateway
guard | gu | Nova guarda
interface | | Nova interface
interceptor | in | Novo interceptor
middleware | mi | Nova Middleware
module | mo | Novo módulo
pipe | pi | Novo pipe
provider | pr | Novo provedor
resolver | r | Novo resolver
service | s | Novo serviço


## Exemplos
> Módulo
```properties
nest g module veiculo
```
> Controler
```properties
nest g controler veiculo/fabricante
```
> Service
```properties
nest g service veiculo/fabricante
```
> Entity
```properties
nest g class veiculo/fabricante/fabricante.entity
```


****

## Build
Compila um aplicativo ou espaço de trabalho para uma pasta de saída.
```properties
nest build
```

****

## Info
Exibe informações sobre pacotes de ninhos instalados e outras informações úteis do sistema.
```properties
nest info|i
```

****

## Update
Atualizar as dependências para última versão.
```properties
nest update|u
```

****

## Add
Importar biblioteca.
```properties
nest add
```











<!--
1. Um
1. Dois
-->
