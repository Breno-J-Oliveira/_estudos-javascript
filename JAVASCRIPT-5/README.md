# 📘 JavaScript — Funções (AULA 5)

<p align="center"><img src="https://img.shields.io/badge/JavaScript-F7DF1E&logo=javascript&logoColor=black?style=for-the-badge"> <img src="https://img.shields.io/badge/HTML5-E34F26&logo=html5&logoColor=white?style=for-the-badge"> <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-10B981?style=for-the-badge"></p>

## 📖 Sobre

Quinta aula de JavaScript dedicada às **funções** — blocos reutilizáveis de código que executam tarefas específicas. Abrange declaração, parâmetros, retorno de valores e arrow functions (ES6+).

## 🧠 Conceitos Abordados

### Declaração de Funções
- `function nome() { }` — declaração clássica
- `const nome = function() { }` — função anônima
- `const nome = () => { }` — arrow function (ES6+)

### Parâmetros e Retorno
- Parâmetros: dados de entrada da função
- `return` — valor que a função devolve
- Parâmetros opcionais com valor padrão
- Funções sem retorno (`void`)

### Callbacks
- Funções passadas como argumento
- Execução assíncrona com callbacks

## 💻 Exemplos de Código

```javascript
// Função clássica com parâmetros e retorno
function soma(a, b) {
  return a + b;
}
console.log(soma(5, 3)); // 8

// Arrow function
const multiplicar = (a, b) => a * b;
console.log(multiplicar(4, 2)); // 8

// Callback
function processar(num, callback) {
  return callback(num);
}
let dobro = processar(5, (n) => n * 2);
console.log(dobro); // 10
```

## 📁 Arquivos
| Arquivo | Descrição |
|---------|-----------|
| `AULA5/` | Pasta com exercícios de funções |


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