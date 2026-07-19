# 📘 JavaScript — Manipulação do DOM (AULA 7)

<p align="center"><img src="https://img.shields.io/badge/JavaScript-F7DF1E&logo=javascript&logoColor=black?style=for-the-badge"> <img src="https://img.shields.io/badge/HTML5-E34F26&logo=html5&logoColor=white?style=for-the-badge"> <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-10B981?style=for-the-badge"></p>

## 📖 Sobre

Sétima aula introduzindo a **manipulação do DOM** (Document Object Model). O foco é selecionar, criar e modificar elementos HTML dinamicamente via JavaScript.

## 🧠 Conceitos Abordados

### Seleção de Elementos
- `document.getElementById('id')` — por ID
- `document.querySelector('seletor')` — primeiro match CSS
- `document.querySelectorAll('seletor')` — todos matches
- `document.getElementsByClassName('classe')`

### Manipulação
- `.innerHTML` — conteúdo HTML
- `.textContent` — conteúdo textual
- `.style.propriedade` — estilos inline
- `.classList.add/remove/toggle()` — classes CSS
- `.setAttribute()` / `.getAttribute()`

### Criação de Elementos
- `document.createElement('tag')` — criar elemento
- `.appendChild()` — adicionar ao DOM
- `.remove()` — remover elemento

## 💻 Exemplos de Código

```javascript
// Selecionar e modificar
const titulo = document.querySelector('h1');
titulo.innerHTML = 'Novo Título';
titulo.style.color = 'blue';

// Criar e adicionar elemento
const novoParagrafo = document.createElement('p');
novoParagrafo.textContent = 'Criado dinamicamente!';
document.body.appendChild(novoParagrafo);
```

## 📁 Arquivos
| Arquivo | Descrição |
|---------|-----------|
| `AULA7/` | Pasta com exercícios de manipulação DOM |


## 👤 Contatos e Redes Sociais

<p align="center">
  <a href="https://github.com/Breno-J-Oliveira" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://www.linkedin.com/in/breno-j-oliveira-672619352/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://www.instagram.com/brenoov" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
  </a>
  <a href="https://x.com/BrenoJOliveira_" target="_blank">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X (Twitter)">
  </a>
</p>

---

<p align="center"><em>Desenvolvido com 💛 por Breno Oliveira — Técnico em Desenvolvimento de Sistemas | SENAI</em></p>