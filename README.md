# {Weather-APP}

## Preview

![Print da aplicação](./public/assets/print1.png)
![Print da aplicação](./public/assets/print2.png)

Este repositório contém um projeto desenvolvido utilizando Node.js, React e TypeScript. Neste arquivo README, você encontrará um guia passo a passo para abrir o projeto em seu ambiente local.

## Pré-requisitos

Antes de começar, verifique se você possui as seguintes ferramentas instaladas em sua máquina:

- Node.js (versão 12 ou superior)
- npm (gerenciador de pacotes do Node.js)

## Passo 1: Clonar o repositório

Comece clonando este repositório para sua máquina local. Abra o terminal e execute o seguinte comando:

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

Isso criará uma cópia local do repositório em seu ambiente.

## Passo 2: Instalar dependências

Navegue até o diretório raiz do projeto e execute o seguinte comando para instalar as dependências do Node.js:

```bash
cd Weather-APP
npm install
```

Esse comando irá ler o arquivo `package.json` e instalar todas as dependências necessárias para o projeto.

## Passo 3: Configurar variáveis de ambiente

O projeto exigi algumas variáveis de ambiente para funcionar corretamente. Verifique o arquivo `.env.example` no diretório raiz do projeto. faça uma cópia desse arquivo e renomeie-o para `.env`. Em seguida, atualize as variáveis de ambiente de acordo com as configurações do seu ambiente local.

## Passo 4: Iniciar o servidor

Para iniciar o servidor Node.js, execute o seguinte comando:

```bash
npm start
```

Isso iniciará o servidor e você poderá acessá-lo através do seu navegador no endereço `http://localhost:8080`.
(ou o que você preferir, se quiser alterar é so ir na pasta `.env.example`(agora renomeada para `.env`)e alterar o "PORT" para o de sua preferência. os mais comuns sao 3000 ou 8080).

## Passo 5: esse projeto não requer React

## Passo 6: Modificar o projeto

Agora que você tem o projeto em execução, você pode fazer modificações no código conforme necessário. Sinta-se à vontade para explorar e adaptar o projeto de acordo com suas necessidades.

## Passo 7: Publicar suas modificações

Se desejar publicar suas modificações em um repositório remoto no GitHub, siga estes passos:

1. Crie um novo repositório vazio no GitHub.
2. No terminal, navegue até o diretório raiz do projeto.
3. Execute os seguintes comandos:

```bash
git remote set-url origin https://github.com/seu-usuario/nome-do-novo-repositorio.git
git add .
git commit -m "Adicionar minhas modificações"
git push -u origin master
```

Isso configurará o repositório remoto e enviará suas modificações para lá.

---
