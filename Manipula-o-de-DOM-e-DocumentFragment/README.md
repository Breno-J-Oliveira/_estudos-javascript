# 🌳 Manipulação de DOM e DocumentFragment

<p align="center">
  <img src="https://img.shields.io/badge/Status-FINALIZADO-10B981?style=for-the-badge&logo=checkmarx&logoColor=white">
  <img src="https://img.shields.io/badge/Versão-1.0-2563EB?style=for-the-badge">
  <img src="https://img.shields.io/badge/Projeto-Atividade%20Acadêmica-111827?style=for-the-badge">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/DOM-Interface-blue?style=for-the-badge">
</p>

---

## 📑 Índice

1. Sobre o Projeto
2. Objetivo da Atividade
3. Exercícios Propostos
4. Funcionalidades Aplicadas
5. Explicação da Resolução
6. Resultado Esperado
7. Requisitos de Instalação
8. Como Executar o Projeto
9. Observações Importantes
10. Contatos e Redes Sociais
11. Conclusão Final
12. Entrega

---

## 🎯 Sobre o Projeto

Este projeto consiste em uma série de exercícios práticos focados na manipulação do **DOM (Document Object Model)** utilizando JavaScript puro. O foco principal é entender como criar elementos dinamicamente e otimizar a renderização usando `DocumentFragment`.

Projeto desenvolvido individualmente por **Breno José de Oliveira**.

---

## ⚙️ Objetivo da Atividade

A atividade teve como finalidade consolidar o conhecimento sobre a árvore do DOM e métodos de inserção de elementos.

Foram executadas as seguintes etapas:
- Criação de elementos HTML via JavaScript (`createElement`).
- Uso do método `appendChild()` para inserção de nós.
- Implementação de `DocumentFragment` para otimização de performance.
- Manipulação de arrays para geração de listas dinâmicas.
- Atribuição de eventos de clique em botões.

---

## 📝 Exercícios Propostos

### Exemplo Prático: Adição Simples
Criação de um botão que, ao ser clicado, adiciona um único item `<li>` com o texto "Novo item" a uma lista existente utilizando `appendChild()`.

### Exercício 2: Lote de Elementos com Fragmento
Criação de um botão "Criar lista" que gera 5 elementos `<li>` de uma vez. Os elementos são agrupados em um `DocumentFragment` antes de serem inseridos no DOM para garantir melhor performance.

### Exercício 3: Renderização de Array
Criação de um botão "Mostrarnomes" que percorre um array de strings, transforma cada nome em um `<li>` e insere todos na página via fragmento.

---

## 🛠 Funcionalidades Aplicadas

Durante a atividade foram utilizados:

- `document.getElementById()`
- `document.createElement()`
- `document.createDocumentFragment()`
- `.appendChild()`
- `.addEventListener('click', ...)`
- Laços de repetição e `forEach()`
- Manipulação de arrays

---

## 🧠 Explicação da Resolução

A lógica aplicada seguiu o princípio de eficiência na renderização. 

Nos **Exercícios 2 e 3**, em vez de adicionar cada item diretamente à lista principal (o que causaria múltiplos redesenhos da página), os itens foram primeiro anexados a um **DocumentFragment**. Este objeto funciona como um container virtual na memória. Somente após todos os itens estarem prontos, esse fragmento foi adicionado à lista com um único `appendChild()`, o que é uma prática recomendada para evitar gargalos de processamento no navegador.

---

## ✅ Resultado Esperado

O sistema deve apresentar:
- Uma interface funcional com listas e botões.
- Adição dinâmica de itens ao clicar nos botões.
- Inserção em lote de elementos (5 itens por vez no Exercício 2).
- Renderização de uma lista de nomes a partir de um array no Exercício 3.

---

## 💻 Requisitos de Instalação

- Navegador Web moderno (Chrome, Edge, Firefox, etc.)
- Editor de código (VS Code recomendado)

---

## 🚀 Como Executar o Projeto

1. Salve os arquivos HTML e JavaScript na mesma pasta.
2. Abra o arquivo `.html` em seu navegador de preferência.
3. Clique nos botões para executar as funções de manipulação de lista.
4. Utilize o **Console do Navegador (F12)** para verificar o comportamento do código.

---

## ⚠️ Observações Importantes

- O uso de `DocumentFragment` é essencial para lidar com grandes volumes de dados no DOM.
- O código foi desenvolvido de forma modular para facilitar a leitura.
- Não foram utilizadas bibliotecas externas, apenas JavaScript puro (Vanilla JS).

---

## 🤝 Contatos e Redes Sociais

<p align="center">
  <a href="https://github.com/Breno-J-Oliveira" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
  </a>
  <a href="https://www.linkedin.com/in/breno-j-oliveira-672619352/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
  <a href="https://www.instagram.com/brenoov" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">
  </a>
  <a href="https://x.com/BrenoJOliveira_" target="_blank">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white">
  </a>
</p>

---

## 🏁 Conclusão Final

A atividade permitiu a prática direta de manipulação de interface via código. A transição do uso simples do `appendChild()` para técnicas mais avançadas como o `DocumentFragment` demonstra o entendimento de como criar aplicações web mais fluidas e otimizadas.

---

## 📌 Entrega

Formato de entrega:
**seunome_sobrenome_dom.docx**

O arquivo deve conter:
- Códigos JavaScript e HTML utilizados.
- Prints do funcionamento no navegador.
- Explicação breve dos métodos utilizados.
