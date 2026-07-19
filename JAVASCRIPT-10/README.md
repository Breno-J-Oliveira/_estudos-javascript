# 📘 JavaScript — Projeto: Galeria de Imagens (AULA 10)

<p align="center"><img src="https://img.shields.io/badge/JavaScript-F7DF1E&logo=javascript&logoColor=black?style=for-the-badge"> <img src="https://img.shields.io/badge/HTML5-E34F26&logo=html5&logoColor=white?style=for-the-badge"> <img src="https://img.shields.io/badge/CSS3-1572B6&logo=css3&logoColor=white?style=for-the-badge"> <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-10B981?style=for-the-badge"></p>

## 📖 Sobre

Último projeto prático do curso de JavaScript: uma **Galeria de Imagens** interativa com grid responsivo, lightbox para visualização ampliada e sistema de filtros por categoria.

## 🎯 Funcionalidades

- 🖼️ **Grid responsivo** de imagens com CSS Grid
- 🔍 **Lightbox** — clique na imagem para visualização ampliada
- 🏷️ **Filtros** por categoria (todos, natureza, cidade, etc.)
- ⬅️➡️ **Navegação** entre imagens no lightbox
- ❌ **Fechar** lightbox (ESC ou clique fora)
- ✨ **Transições suaves** com CSS

## 💻 Código de Exemplo

```javascript
// Abrir lightbox
function abrirLightbox(index) {
  lightbox.style.display = 'flex';
  imagemAtual = index;
  atualizarImagemLightbox();
}

// Filtrar por categoria
function filtrar(categoria) {
  const imagens = document.querySelectorAll('.galeria-item');
  imagens.forEach(img => {
    if (categoria === 'todos' || img.dataset.categoria === categoria) {
      img.style.display = 'block';
    } else {
      img.style.display = 'none';
    }
  });
}
```

## 💡 Conceitos Aplicados
- CSS Grid para layout responsivo
- Eventos de teclado (`keydown` para ESC)
- `data-*` attributes para categorias
- Transições e animações CSS
- Manipulação dinâmica de classes

## 📁 Arquivos
| Arquivo | Descrição |
|---------|-----------|
| `index.html` | Estrutura da galeria |
| `style.css` | Grid, lightbox, animações |
| `script.js` | Lógica de interação |
| `img/` | Imagens da galeria |


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