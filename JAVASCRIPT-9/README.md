# 📘 JavaScript — Projeto: Lista de Tarefas (AULA 9)

<p align="center"><img src="https://img.shields.io/badge/JavaScript-F7DF1E&logo=javascript&logoColor=black?style=for-the-badge"> <img src="https://img.shields.io/badge/HTML5-E34F26&logo=html5&logoColor=white?style=for-the-badge"> <img src="https://img.shields.io/badge/CSS3-1572B6&logo=css3&logoColor=white?style=for-the-badge"> <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-10B981?style=for-the-badge"></p>

## 📖 Sobre

Projeto prático que consolida todos os conhecimentos adquiridos nas aulas anteriores. Uma **aplicação To-Do List** completa com funcionalidades CRUD e persistência via `localStorage`.

## 🎯 Funcionalidades

- ✅ **Adicionar** novas tarefas via formulário
- ✅ **Marcar como concluída** com checkbox ou clique
- ✅ **Remover** tarefas individualmente
- ✅ **Persistência** com `localStorage` (dados sobrevivem ao refresh)
- ✅ **Interface limpa** com feedback visual
- ✅ **Contador** de tarefas pendentes/concluídas

## 💻 Código de Exemplo

```javascript
// Salvar tarefas no localStorage
function salvarTarefas() {
  localStorage.setItem('tarefas', JSON.stringify(listaTarefas));
}

// Carregar tarefas ao iniciar
function carregarTarefas() {
  const dados = localStorage.getItem('tarefas');
  if (dados) {
    listaTarefas = JSON.parse(dados);
    renderizarLista();
  }
}

// Adicionar nova tarefa
function adicionarTarefa(texto) {
  listaTarefas.push({
    id: Date.now(),
    texto: texto,
    concluida: false
  });
  salvarTarefas();
  renderizarLista();
}
```

## 💡 Conceitos Aplicados
- Manipulação do DOM
- Eventos (`click`, `submit`)
- Arrays e objetos
- `localStorage` API
- JSON serialização
- Funções modulares

## 📁 Arquivos
| Arquivo | Descrição |
|---------|-----------|
| `index.html` | Interface do To-Do List |
| `style.css` | Estilização |
| `script.js` | Lógica completa |


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