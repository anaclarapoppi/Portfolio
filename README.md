# 💼 Portfólio / Currículo Web

## 📋 Sobre o Projeto

Este projeto consiste no desenvolvimento de uma página de **Portfólio / Currículo Web** utilizando **HTML5 puro e semântico**.

A página foi criada para apresentar informações pessoais, habilidades, projetos desenvolvidos e um formulário de contato, demonstrando conhecimentos básicos de estruturação de páginas Web.

## 🎯 Objetivo

Criar uma página HTML limpa, organizada e funcional, utilizando corretamente as principais **tags semânticas do HTML5** e seguindo a estrutura proposta no desafio.

## 🛠️ Tecnologias Utilizadas

* HTML5
* Tags semânticas
* Tabelas HTML
* Formulários
* Links internos
* Hiperlinks
* Imagens

## 📌 Estrutura do Projeto

A página é organizada nas seguintes seções:

### 🏠 Cabeçalho e Navegação

Contém o título principal com o nome/cargo do desenvolvedor e um menu de navegação com links para:

* Sobre Mim
* Meus Projetos
* Entre em Contato

### 👤 Sobre Mim

Apresenta:

* Foto de perfil com tamanho de **150x150 pixels**;
* Texto de apresentação;
* Lista de habilidades do desenvolvedor.

### 💻 Meus Projetos

Apresenta uma tabela organizada com as informações dos projetos:

| Projeto   | Tecnologias | Status       | Link    |
| --------- | ----------- | ------------ | ------- |
| Projeto 1 | HTML5       | Concluído    | Acessar |
| Projeto 2 | HTML5       | Em andamento | Acessar |
| Projeto 3 | HTML5       | Concluído    | Acessar |

A tabela utiliza as tags `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>` e `<td>`.

### 📩 Entre em Contato

A seção possui um formulário agrupado dentro de um `<fieldset>` com o título **"Dados do Contato"**.

O formulário contém:

* Campo para Nome;
* Campo para Email;
* Menu suspenso para Assunto;
* Área de texto para Mensagem;
* Botão de envio.

Todos os campos possuem seus respectivos `<label>` vinculados.

### 📄 Rodapé

O rodapé apresenta:

* Direitos autorais utilizando o caractere especial **©**;
* E-mail de contato;
* Telefone de contato.

## 🔧 Especificações Técnicas

O projeto utiliza HTML5 semântico, incluindo:

```html
<header>
<nav>
<main>
<section>
<table>
<fieldset>
<footer>
```

A imagem de perfil possui:

```html
width="150"
height="150"
```

A navegação utiliza âncoras internas, por exemplo:

```html
<a href="#sobre">Sobre Mim</a>
```

## 📁 Arquivos

```text
📁 projeto/
│
├── index.html
├── README.md
└── 📁 imagens/
    └── foto-perfil.jpg
```

## 🚀 Como Executar

1. Baixe ou clone este projeto.
2. Abra a pasta do projeto.
3. Abra o arquivo `index.html` em qualquer navegador.
4. Navegue pelas seções utilizando o menu.

## 🏆 Requisitos Atendidos

* ✅ Estrutura HTML5;
* ✅ Uso de tags semânticas;
* ✅ Cabeçalho e menu de navegação;
* ✅ Seção "Sobre Mim";
* ✅ Foto de perfil 150x150px;
* ✅ Lista de habilidades;
* ✅ Tabela de projetos;
* ✅ Links funcionais;
* ✅ Formulário de contato;
* ✅ Uso de `<fieldset>` e `<legend>`;
* ✅ Campos com `<label>`;
* ✅ Rodapé com caractere especial ©;
* ✅ E-mail e telefone de contato.

## 👩‍💻 Autoria

Projeto desenvolvido como atividade de **Desenvolvimento Web**, com foco na prática de estruturação de páginas utilizando HTML5.
