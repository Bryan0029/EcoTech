# 🌱 EcoTech — Landing Page
> Landing page para a EcoTech, startup fictícia de sustentabilidade que permite trocar lixo reciclável por créditos de energia.

![status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![html](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![css](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

---

## 📖 Sobre o projeto
Projeto final da disciplina de Web Design, com o desafio de transformar o site de uma startup fictícia (backend já pronto, front-end desorganizado) em uma landing page profissional, responsiva e interativa, dentro do prazo de lançamento.

**Demo:** _(adicionar link do GitHub Pages aqui depois do deploy)_
**Preview:** _(adicionar screenshot aqui depois de pronto)_

---

## ✅ Checklist de exigências técnicas

### 1. Estrutura e semântica (HTML5)
- [x] Tags semânticas: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`
- [x] Formulário de captura de leads com `required` e `type="email"`

### 2. Layout avançado e responsivo (CSS3)
- [ ] CSS Grid na estrutura geral (ex: seção de benefícios) — **pendente**
- [x] Flexbox nos alinhamentos internos (ex: menu de navegação)
- [x] `@media queries` para adaptar mobile/desktop
- [ ] Sem barra de rolagem horizontal em telas pequenas — **a validar**

### 3. Organização e escalabilidade (variáveis CSS)
- [x] Bloco `:root` no topo do CSS
- [x] Pelo menos 3 cores em variável (primária, secundária, fundo)
- [x] Fonte(s) em variável
- [ ] `border-radius` padrão em variável — **pendente** (hardcoded em `.button-banner` e `.hero`)
- [x] Nenhum hex solto fora do `:root`

### 4. Microinterações (transições e animações)
- [x] `transition` suave em botões e links de navegação (hover)
- [ ] `transform: scale(1.05)` nos cards de benefícios ao hover/foco — **pendente** (cards ainda não criados)
- [ ] Pelo menos 1 animação contínua com `@keyframes` — **pendente**

### 5. Qualidade geral
- [x] Código indentado e organizado
- [x] Sem estilos inline
- [x] Sem `<div>` para tudo (semântica correta)

---

## 🗂️ Estrutura sugerida da página
| Seção | Conteúdo | Status |
|---|---|---|
| Header | Logo + menu (Home, Benefícios, Como Funciona, Contato) | ✅ Feito |
| Hero | Frase de impacto, imagem ilustrativa, CTA com animação pulsante | 🟡 Falta imagem e animação |
| Benefícios | 3–4 cards em grid, com hover | 🔴 Seção vazia |
| Como Funciona | Explicação do funcionamento da plataforma | 🔴 Seção vazia |
| Formulário | Campo de e-mail para captura de leads | ✅ Feito |
| Footer | Direitos autorais + links sociais fictícios | 🟡 Falta links sociais |

---

## 📁 Estrutura de pastas
```
ecotech-landing/
├── index.html
├── style/
│   └── styles.css
├── /assets
│   ├── /img
│   └── /icons
└── README.md
```

---

## 🛠️ Tecnologias
- HTML5 semântico
- CSS3 (Grid, Flexbox, variáveis, `@keyframes`)
- Sem frameworks ou bibliotecas externas

---

## ▶️ Como rodar localmente
```bash
git clone https://github.com/seu-usuario/ecotech-landing.git
cd ecotech-landing
```
Depois, basta abrir o `index.html` no navegador (ou usar a extensão Live Server do VS Code).

---

## 👤 Autor
Bryan — Curso de Desenvolvimento Web, IFNMG
