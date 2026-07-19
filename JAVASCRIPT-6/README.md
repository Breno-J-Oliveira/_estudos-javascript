# 📘 JavaScript — Objetos e JSON (AULA 6)

<p align="center"><img src="https://img.shields.io/badge/JavaScript-F7DF1E&logo=javascript&logoColor=black?style=for-the-badge"> <img src="https://img.shields.io/badge/HTML5-E34F26&logo=html5&logoColor=white?style=for-the-badge"> <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-10B981?style=for-the-badge"></p>

## 📖 Sobre

Sexta aula focada em **objetos JavaScript** — estruturas que agrupam dados e funcionalidades relacionadas. Abrange criação de objetos, acesso a propriedades, métodos e serialização com JSON.

## 🧠 Conceitos Abordados

### Objetos
- Criação: `{ chave: valor }`
- Acesso: `obj.propriedade` ou `obj["propriedade"]`
- Métodos: funções dentro de objetos
- Palavra-chave `this`

### JSON (JavaScript Object Notation)
- `JSON.stringify(obj)` — objeto → string JSON
- `JSON.parse(string)` — string JSON → objeto
- Formato universal de troca de dados

## 💻 Exemplos de Código

```javascript
// Objeto com propriedades e método
const pessoa = {
  nome: "Breno",
  idade: 18,
  curso: "Desenvolvimento de Sistemas",
  saudacao() {
    return `Olá, sou ${this.nome} e tenho ${this.idade} anos`;
  }
};
console.log(pessoa.saudacao());

// Conversão JSON
const json = JSON.stringify(pessoa);
console.log(json);
const objetoDeVolta = JSON.parse(json);
```

## 📁 Arquivos
| Arquivo | Descrição |
|---------|-----------|
| `AULA6/` | Pasta com exercícios de objetos e JSON |


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