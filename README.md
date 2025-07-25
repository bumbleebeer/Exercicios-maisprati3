# Lista de Exercícios 3 – Desenvolvimento Web Básico  

Lista de exercícios do módulo 2 do curso +Prati onde abordamos a linguagem de marcação de texto HTML e estilizações com o CSS

Para acessar o projeto use:
```bash
  git clone https://github.com/bumbleebeer/Exercicios-maisprati3
```
Selecione com o botão direito um dos arquivos .html, se tiver a extenção Live Server selecione a opção Show Preview, caso contrário vá na pasta clonada e execute o arquivo que irá abrir o navegador


# 🛠️ Tecnologias Utilizadas

- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS&logoColor=white)

-   ![JavaScript](https://shields.io/badge/JavaScript-F7DF1E?logo=JavaScript&logoColor=white)



# 📌 Tasks

## 📄 Crie um arquivo chamado `index.html` e monte nele a seguinte estrutura usando sempre tags semânticas:

- Um `<header>` contendo um `<h1>` (título) e um `<p>` (parágrafo) introdutório.
- Um `<main>` dividido em duas subseções:
  - Seção “📌 Missão” com `<h2>` e `<p>`.
  - Seção “🎯 Visão” com `<h2>` e `<p>`.
- Um `<footer>` com um `<p>` de copyright.

---

## 📋 Listas e Navegação - Em um arquivo `listas.html`:

- Crie uma lista **não ordenada** (`<ul>`) com cinco hobbies seus, cada um em um `<li>`.
- Crie uma lista **ordenada** (`<ol>`) descrevendo, em passos, como preparar uma receita simples, cada passo em um `<li>`.
- Ao final, inclua um bloco de **navegação** (`<nav>`) com três **links externos**, usando:
  ```html
  <a href="URL_DO_SITE">Nome do Site</a>
  ```

---

## 📝 Formulário de Feedback - Em `feedback.html`:

- Crie um formulário com os seguintes campos:
  - 👤 Nome
  - 📧 E-mail
  - 🏠 Endereço Completo
  - 📂 Tipo de feedback (select)
  - 💬 Campo para o Feedback (textarea)
  - 📤 Botão de Envio

---

## 🎨 CSS Básico e Box Model - Em `styles.css` vinculado ao `index.html`:

- Defina **cores de fundo** (`background-color`) e de **texto** (`color`) para:
  - `<header>`
  - `<main>`
  - `<footer>`
- Para cada uma dessas seções, aplique:
  - `margin`
  - `padding`
  - `border` Para evidenciar seus contornos.

---

## 🎯 Seletores e Propriedades (em `styles.css`):

- Estilo para todas as tags `<h2>`:

  - `font-size` maior
  - `text-decoration: underline`

- Classe `.destaque`:

  - `font-style: italic`
  - `background-color` leve

- ID `#importante`:

  - `border-top` mais espessa

---

## 🖼️ Exercício Grid e Flexbox - Galeria com imagens:

- Monte uma galeria com **8 imagens e legendas**.
- Use **CSS Grid** para organizar as imagens.
- Use **Flexbox** no contêiner para centralizar e permitir quebra de linha quando a largura da tela for pequena.
- Use **media query** para ajustar o número de colunas em telas menores.

---

## 🍔 Menu Hamburger:

- Implemente um menu que:
  - Aparece **apenas** em telas com largura **≤ 600px**
  - **Oculta** a navegação padrão
  - Abre/fecha o menu ao ser **clicado**

