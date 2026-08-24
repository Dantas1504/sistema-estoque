# 🍕 Sistema de Estoque - Pizzaria

Sistema web desenvolvido para auxiliar no controle de estoque e gerenciamento de produtos de uma pizzaria.

O projeto foi desenvolvido com foco em facilitar o acompanhamento dos produtos, movimentações de estoque e organização das informações em um sistema centralizado.

## 🚀 Tecnologias utilizadas

* HTML5
* CSS3
* JavaScript
* Firebase Authentication
* Firebase Realtime Database
* Progressive Web App (PWA)
* Service Worker

## 📋 Funcionalidades

* 🔐 Sistema de autenticação de usuários
* 📦 Controle de estoque
* ➕ Registro de entrada de produtos
* ➖ Registro de saída de produtos
* 📊 Consulta de movimentações
* 📈 Cálculo de saldos e médias
* 🏪 Organização dos dados por loja
* 💾 Armazenamento dos dados em tempo real
* 📱 Interface adaptada para diferentes dispositivos
* ⚡ Funcionamento como aplicação web instalável (PWA)

## 🏗️ Estrutura do projeto

```text
APP PIZZARIA/
├── index.html
├── manifest.json
├── sw.js
├── favicon.png
├── icon-180.png
├── icon-192.png
└── icon-512.png
```

## 🔥 Firebase

O sistema utiliza o Firebase para autenticação e armazenamento dos dados.

### Authentication

O Firebase Authentication é utilizado para controlar o acesso dos usuários ao sistema.

### Realtime Database

Os dados do sistema são armazenados no Firebase Realtime Database, permitindo que as informações sejam sincronizadas em tempo real.

As regras de segurança do banco exigem autenticação para leitura e escrita dos dados.

## 💻 Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/Dantas1504/sistema-estoque.git
```

### 2. Entre na pasta

```bash
cd sistema-estoque
```

### 3. Abra o projeto

Como o projeto utiliza HTML, CSS e JavaScript, ele pode ser executado utilizando um servidor local.

No VS Code, uma opção simples é utilizar a extensão **Live Server**.

## 🔐 Segurança

As credenciais de acesso dos usuários não ficam armazenadas diretamente no código-fonte.

O projeto utiliza o Firebase Authentication para autenticação.

As regras do Firebase Realtime Database também exigem que o usuário esteja autenticado para realizar operações no banco.

> ⚠️ Este projeto utiliza um banco Firebase real. Para utilizar o sistema em outro ambiente, é necessário configurar seu próprio projeto Firebase e suas respectivas regras de segurança.

## 📱 PWA

O sistema possui recursos de Progressive Web App, permitindo que a aplicação possa ser instalada em dispositivos compatíveis.

O projeto utiliza:

* `manifest.json`
* Service Worker
* Ícones para instalação

## 🎯 Objetivo do projeto

Este projeto foi desenvolvido para solucionar uma necessidade real de gerenciamento de estoque em uma pizzaria, utilizando tecnologias web e serviços em nuvem.

Além da aplicação prática, o projeto representa uma experiência de desenvolvimento envolvendo:

* Desenvolvimento Front-end
* JavaScript
* Banco de dados em tempo real
* Autenticação
* Aplicações PWA
* Integração com serviços Firebase

## 👨‍💻 Desenvolvedor

**Iury Reis Dantas**

Estudante de Engenharia de Software e Desenvolvimento de Sistemas.

### 🔗 GitHub

https://github.com/Dantas1504

---

⭐ Se este projeto foi útil ou interessante para você, considere deixar uma estrela no repositório.
