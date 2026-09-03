# 🍕 Sistema de Controle de Estoque 

Sistema web desenvolvido para auxiliar no controle de estoque de uma pizzaria, permitindo acompanhar produtos, registrar entradas e saídas e consultar o histórico das movimentações.

O projeto foi desenvolvido com foco em uma necessidade prática de organização e controle de estoque, utilizando **JavaScript** no desenvolvimento da aplicação e **Firebase** para autenticação e armazenamento dos dados.

## 📸 Sobre o projeto

A aplicação foi pensada para tornar o acompanhamento do estoque mais simples e centralizado.

O usuário pode consultar a quantidade disponível de produtos, registrar movimentações e acompanhar informações do estoque em tempo real.

O sistema possui diferentes categorias de produtos, permitindo organizar o estoque de acordo com a operação da pizzaria.

## 🚀 Funcionalidades

### 🔐 Autenticação

* Login utilizando Firebase Authentication
* Controle de acesso para usuários autenticados
* Encerramento de sessão

### 📦 Controle de estoque

* Visualização dos produtos cadastrados
* Quantidade disponível em estoque
* Organização por categorias
* Identificação de produtos com estoque baixo
* Atualização dos dados em tempo real

### 🔄 Movimentações

* Registro de entradas
* Registro de saídas
* Validação da quantidade disponível antes de uma saída
* Histórico das movimentações
* Exclusão de movimentações

### 📊 Dashboard

O sistema apresenta informações gerais do estoque, incluindo:

* Total de itens em estoque
* Movimentações realizadas no dia
* Produtos com estoque baixo
* Produtos e movimentações por categoria

### 📁 Exportação de dados

A aplicação permite exportar informações do estoque em diferentes formatos:

* CSV
* Excel
* Relatório completo em HTML

O relatório também reúne informações do histórico e dados do estoque.

## 🛠️ Tecnologias utilizadas

| Tecnologia                     | Utilização                                    |
| ------------------------------ | --------------------------------------------- |
| **HTML5**                      | Estrutura da aplicação                        |
| **CSS3**                       | Estilização e responsividade                  |
| **JavaScript**                 | Lógica e funcionalidades do sistema           |
| **Firebase Authentication**    | Autenticação dos usuários                     |
| **Firebase Realtime Database** | Armazenamento dos dados                       |
| **SheetJS (XLSX)**             | Exportação para Excel                         |
| **Service Worker**             | Recursos de PWA e funcionamento offline/cache |

## 🧠 Principais conceitos aplicados

Durante o desenvolvimento, foram colocados em prática conceitos como:

* Manipulação do DOM
* Eventos e formulários
* Operações CRUD
* Autenticação de usuários
* Integração com banco de dados
* Consumo de APIs
* Validação de dados
* Organização de informações por categorias
* Controle de estado da aplicação
* Geração de arquivos
* Desenvolvimento responsivo
* PWA e Service Workers

## 📱 PWA

O projeto possui configuração para **Progressive Web App (PWA)** através de `manifest.json` e `Service Worker`.

Isso permite que a aplicação tenha características de um aplicativo web instalável e utilize recursos de cache definidos pelo Service Worker.

## 📂 Estrutura atual

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

A aplicação atualmente concentra a interface, estilos e lógica principal no `index.html`, enquanto o `manifest.json` e o `sw.js` são responsáveis pela configuração do PWA.

## ▶️ Como executar

Por ser uma aplicação web, o projeto pode ser executado utilizando um servidor local.

### 1. Clone o repositório

```bash
git clone https://github.com/Dantas1504/sistema-estoque.git
```

### 2. Acesse a pasta

```bash
cd sistema-estoque
```

### 3. Execute com um servidor local

Uma opção é utilizar a extensão **Live Server** no Visual Studio Code.

Depois, abra a aplicação pelo endereço fornecido pelo servidor local.

> Para utilizar a autenticação e o banco de dados, é necessário configurar um projeto próprio no Firebase e utilizar suas respectivas credenciais e regras de acesso.

## 🔒 Segurança

O projeto utiliza o **Firebase Authentication** para identificar os usuários e o **Firebase Realtime Database** para persistência dos dados.

As informações de autenticação não ficam armazenadas diretamente no código da aplicação.

Em uma utilização real em produção, as regras do Firebase devem ser configuradas de acordo com os níveis de acesso necessários para cada usuário e ambiente.

## 🎯 Objetivo do projeto

Este projeto foi desenvolvido como uma forma de aplicar na prática conhecimentos adquiridos durante meus estudos em **Engenharia de Software** e desenvolvimento web.

Mais do que criar uma interface, o objetivo foi entender como diferentes partes de uma aplicação se conectam: autenticação, banco de dados, regras de negócio, interface e armazenamento das informações.

## 📚 O que aprendi

O desenvolvimento deste projeto me permitiu aprofundar conhecimentos em **JavaScript**, principalmente na manipulação de dados, criação de funcionalidades e integração com serviços externos.

Também tive contato mais próximo com o Firebase e com situações que aparecem durante o desenvolvimento de uma aplicação real, como validação de operações, organização dos dados e controle de acesso.

## 🔮 Próximos passos

Algumas melhorias que podem ser implementadas futuramente:

* Separação do JavaScript em módulos
* Separação dos estilos em arquivos CSS
* Melhor organização da estrutura do projeto
* Diferentes níveis de permissão para usuários
* Melhorias na experiência de uso
* Novos relatórios e indicadores
* Testes automatizados

## 👨‍💻 Desenvolvedor

**Iury Reis Dantas**

Estudante de Engenharia de Software, interessado em desenvolvimento de software e buscando evoluir através de projetos práticos.

### 🔗 Links

* **GitHub:** https://github.com/Dantas1504
* **Repositório:** https://github.com/Dantas1504/sistema-estoque

---

⭐ Se este projeto foi útil ou interessante para você, fique à vontade para deixar uma estrela no repositório.
