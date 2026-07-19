# 📘 JavaScript — Operadores e Condicionais (AULA 2)

<p align="center"><img src="https://img.shields.io/badge/JavaScript-F7DF1E&logo=javascript&logoColor=black?style=for-the-badge"> <img src="https://img.shields.io/badge/HTML5-E34F26&logo=html5&logoColor=white?style=for-the-badge"> <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-10B981?style=for-the-badge"></p>

## 📖 Sobre

Segunda aula de JavaScript focada em **operadores** e **estruturas condicionais**. O projeto explora como tomar decisões no código usando `if`, `else if`, `else` e `switch case`.

## 🧠 Conceitos Abordados

### Operadores
- **Aritméticos:** `+`, `-`, `*`, `/`, `%` (módulo)
- **Comparação:** `==`, `!=`, `>`, `<`, `>=`, `<=`
- **Igualdade estrita:** `===` vs `==`
- **Lógicos:** `&&` (AND), `||` (OR), `!` (NOT)

### Estruturas Condicionais
- `if` / `else if` / `else` — decisões encadeadas
- `switch case` — múltiplas opções
- Operador ternário: `condição ? valorTrue : valorFalse`

## 💻 Exemplos de Código

```javascript
// Exemplo 1: Verificação de idade
let idade = parseInt(prompt("Digite sua idade:"));
if (idade >= 18) {
  console.log("Maior de idade");
} else if (idade >= 16) {
  console.log("Pode votar");
} else {
  console.log("Menor de idade");
}

// Exemplo 2: Switch para dia da semana
let dia = parseInt(prompt("Dia (1-7):"));
switch(dia) {
  case 1: console.log("Domingo"); break;
  case 7: console.log("Sábado"); break;
  default: console.log("Dia útil");
}
```

## 📁 Arquivos
| Arquivo | Descrição |
|---------|-----------|
| `AULA2/` | Pasta com exercícios práticos |


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