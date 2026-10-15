# 🥐 Padaria Pão & Cia

![Status do Projeto](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)
![Licença](https://img.shields.io/badge/Licen%C3%A7a-MIT-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

> *"Feito com fermento natural e muito carinho, todos os dias."* — Equipe da Padaria Pão & Cia

Este repositório contém o código-fonte do site institucional e cardápio online da **Padaria Pão & Cia** ("A melhor padaria de Londrina"), desenvolvido como projeto acadêmico no **CEEP Castaldi** em 2026.

---

## 📋 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Páginas e Funcionalidades](#-páginas-e-funcionalidades)
- [Tecnologias e Conceitos Utilizados](#-tecnologias-e-conceitos-utilizados)
- [Estrutura de Arquivos](#-estrutura-de-arquivos)
- [Como Executar o Projeto](#-como-executar-o-projeto)
- [Licença e Autoria](#-licença-e-autoria)

---

## 📖 Sobre o Projeto

O projeto consiste em um site estático multipágina criado para apresentar uma padaria artesanal localizada em Londrina/PR. O objetivo principal é praticar a estruturação semântica com **HTML5** e a estilização moderna com **CSS3**, utilizando boas práticas como tabelas acessíveis, citações semânticas e layouts em Flexbox.

---

## ✨ Páginas e Funcionalidades

### 1. Página Inicial (`index.html`)
- **Cabeçalho e Navegação:** Identidade visual da padaria e menu de navegação rápida por âncoras (`#destaques`, `#cardapio`, `#contato`).
- **Apresentação:** Seção introdutória utilizando tags semânticas de citação e ênfase (`<blockquote>`, `<cite>`, `<strong>`, `<em>`).
- **Destaques do Dia:** Exibição de cards estilizados com Flexbox apresentando fotos e descrições dos produtos principais:
  - *Pão de Mel Artesanal*
  - *Bolo de Fubá com Goiabada*
  - *Coxinha com Catupiry*
- **Resumo do Cardápio:** Tabela organizada por categorias (*Doces, Bolos, Salgados e Sobremesas*) com exemplos de produtos.
- **Rodapé:** Informações de endereço, telefone de contato e créditos de desenvolvimento.

### 2. Página de Cardápio (`cardapio.html`)
- **Catálogo Detalhado com Preços:** Tabelas semânticas separadas por seções para facilitar a leitura dos clientes:
  - 🍬 **Doces:** Pão de Mel Artesanal (R$ 8,00), Brigadeiro Gourmet (R$ 5,00).
  - 🍰 **Bolos:** Bolo de Fubá com Goiabada (R$ 7,00), Bolo de Chocolate Supremo (R$ 9,00).
  - 🥟 **Salgados:** Coxinha de Frango com Catupiry (R$ 8,00), Pão de Queijo Mineiro (R$ 4,00).
  - 🍮 **Sobremesas:** Pudim de Leite Condensado (R$ 10,00), Taça da Felicidade (R$ 12,00).

---

## 🚀 Tecnologias e Conceitos Utilizados

- **HTML5 Semântico:** Uso de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<blockquote>` e tabelas estruturadas com `<caption>`, `<thead>`, `<tbody>` e `<th scope="col">`.
- **CSS3 (`style.css`):** Estilização compartilhada entre as páginas, layout responsivo com Flexbox para os cards de destaques e formatação de tabelas.
- **Git & GitHub:** Controle de versão e hospedagem do código.

---

## 📂 Estrutura de Arquivos

```text
📦 Padaria
 ┣ 📜 index.html                                      # Página principal (Home)
 ┣ 📜 cardapio.html                                   # Página com o cardápio detalhado e preços
 ┣ 📜 style.css                                       # Folha de estilo compartilhada pelas páginas
 ┣ 🖼️ Captura de tela_2026-08-07_08-24-29.png         # Foto do Pão de Mel Artesanal
 ┣ 🖼️ coxinha-de-frango1.jpg                          # Foto da Coxinha de Frango com Catupiry
 ┣ 🖼️ imagem.jpg                                      # Foto do Bolo de Fubá com Goiabada
 ┣ 🖼️ Imagem-ilustrativa-de-bolo-de-fuba_milho.webp   # Imagem ilustrativa de bolo de fubá
 ┣ 🖼️ maxresdefault.jpg / maxresdefault (1).jpg       # Imagens adicionais do projeto
 ┣ 📜 LICENSE                                         # Licença MIT do repositório
 ┗ 📜 README.md                                       # Documentação do projeto
```

---

## 🔧 Como Executar o Projeto

1. **Clone este repositório:**
   ```bash
   git clone [https://github.com/anajerominequeiroz-ctrl/Padaria.git](https://github.com/anajerominequeiroz-ctrl/Padaria.git)
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd Padaria
   ```

3. **Abra no navegador:**
   Basta dar dois cliques no arquivo `index.html` para abri-lo em qualquer navegador web (ou utilizar a extensão *Live Server* no VS Code).

---

## 📄 Licença e Autoria

Este projeto está sob a licença **MIT** — veja o arquivo [LICENSE](LICENSE) para mais detalhes.

- **Autora:** Ana Luiza ([@anajerominequeiroz-ctrl](https://github.com/anajerominequeiroz-ctrl))
- **Instituição:** CEEP Castaldi (2026)
