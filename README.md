# 📗 Estudos de JavaScript — Do zero às aplicações interativas

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="ES6+">
  <img src="https://img.shields.io/badge/DOM-555555?style=for-the-badge&logo=html5&logoColor=white" alt="DOM">
  <img src="https://img.shields.io/badge/localStorage-FFA500?style=for-the-badge&logo=javascript&logoColor=white" alt="localStorage">
  <br>
  <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-10B981?style=flat-square" alt="Status">
  <img src="https://img.shields.io/badge/Projectos-11-2563EB?style=flat-square" alt="Projectos">
  <img src="https://img.shields.io/badge/N%C3%ADvel-Iniciante%20a%20Intermedi%C3%A1rio-F59E0B?style=flat-square" alt="Nível">
  <img src="https://img.shields.io/badge/Dura%C3%A7%C3%A3o-~10%20semanas-8B5CF6?style=flat-square" alt="Duração">
  <img src="https://img.shields.io/badge/Institui%C3%A7%C3%A3o-SENAI-EF4444?style=flat-square" alt="SENAI">
</p>

---

## O que é esta categoria?

A categoria **Estudos de JavaScript** é o registo completo da minha jornada de aprendizagem de JavaScript durante o curso de **Desenvolvimento de Sistemas no SENAI**. São **11 projectos** organizados em ordem progressiva de dificuldade — do primeiro `console.log` até aplicações web completas com manipulação do DOM, eventos e armazenamento local.

Cada projecto foca num conceito específico da linguagem, com exemplos práticos, comentários no código e um README próprio que explica o que foi aprendido. É essencialmente um **currículo de JavaScript** documentado passo a passo.

**Plug-and-play para estudos:** qualquer pessoa pode clonar este repositório, abrir os ficheiros HTML no navegador e ver o código a funcionar — sem instalar nada.

---

## O que esta categoria entrega?

### Para o estudante de JavaScript
- **Sintaxe fundamental** — variáveis, tipos de dados, operadores, condicionais
- **Estruturas de controlo** — laços `for`, `while`, `do-while`
- **Arrays e métodos funcionais** — `push`, `pop`, `map`, `filter`, `reduce`
- **Funções** — declaração, expressão, arrow functions, parâmetros, `return`
- **Objetos e JSON** — propriedades, métodos, `this`, `JSON.parse`/`stringify`
- **Manipulação do DOM** — `querySelector`, `createElement`, `innerHTML`, classes
- **Eventos** — `click`, `submit`, `keydown`, `input`, delegação de eventos
- **Armazenamento local** — `localStorage` com operações CRUD
- **DocumentFragment** — optimização de performance no DOM
- **Projectos práticos completos** — Lista de Tarefas e Galeria de Imagens

### Para o recrutador / avaliador
- **Progressão visível** — do básico ao avançado em 11 etapas documentadas
- **Código comentado** — cada ficheiro explica o que está a acontecer
- **README por projecto** — objectivos, conceitos, estrutura e capturas
- **Exemplos executáveis** — abre o `.html` no navegador e vê a funcionar
- **Boas práticas** — nomes claros, formatação consistente, separação de responsabilidades
- **Padrões reais** — `localStorage` CRUD, delegação de eventos, `DocumentFragment`

---

## Como funciona? — Percurso de Aprendizagem

### 🔰 Fase 1 — Fundamentos (Projectos 1–3)

```
1. Variáveis, tipos de dados, console.log, alert, prompt
       ↓
2. Operadores aritméticos, relacionais, lógicos
   Condicionais: if, else if, else, switch
       ↓
3. Laços de repetição: for, while, do-while
   Iteração, contadores, acumuladores
```

**Objectivo:** dominar a sintaxe base. Escrever código que compila, entender fluxo de execução e resolver problemas simples com condicionais e laços.

### 🟡 Fase 2 — Estruturas de Dados e Funções (Projectos 4–6)

```
4. Arrays: criação, acesso por índice, métodos push/pop/shift/unshift
   Métodos funcionais: map, filter, reduce, forEach
       ↓
5. Funções: declaração vs expressão, parâmetros, argumentos
   Arrow functions, return implícito, scope
       ↓
6. Objetos literais, propriedades e métodos
   JSON: parse, stringify, APIs
```

**Objectivo:** trabalhar com coleções de dados, escrever código reutilizável com funções e modelar dados com objectos.

### 🟢 Fase 3 — O Navegador como Plataforma (Projectos 7–8)

```
7. DOM: querySelector, querySelectorAll, getElementById
   Criar elementos dinamicamente, innerHTML vs createElement
   Classes CSS via classList (add, remove, toggle)
       ↓
8. Eventos: addEventListener, objeto event
   Click, submit, keydown, input, change
   Delegação de eventos em listas dinâmicas
```

**Objectivo:** sair do terminal e interagir com o navegador. Manipular HTML/CSS via JavaScript e responder a acções do utilizador.

### 🔵 Fase 4 — Projectos Práticos (Projectos 9–10 + Extra)

```
9. Lista de Tarefas — CRUD completo com localStorage
   Adicionar, editar, remover, marcar como concluída
       ↓
10. Galeria de Imagens — Grid CSS + Lightbox + Filtros
        ↓
Extra. DocumentFragment — Optimização de performance no DOM
      Renderização em massa sem múltiplos reflows
```

**Objectivo:** integrar todos os conhecimentos em aplicações completas que resolvem problemas reais.

---

## Arquitectura da Categoria

```
_estudos-javascript/
│
├── README.md                          ← Este ficheiro (índice geral)
│
├── JAVASCRIPT/                        ← Projecto 1 — Fundamentos
│   ├── README.md
│   ├── DIA1/                          ← Primeiros exercícios
│   └── DIA 1 2.0/                     ← Revisão e reforço
│
├── JAVASCRIPT-2/                      ← Projecto 2 — Operadores e Condicionais
│   ├── README.md
│   └── index.html                     ← Exemplos executáveis
│
├── JAVASCRIPT-3/                      ← Projecto 3 — Laços de Repetição
│   ├── README.md
│   └── DIA 2/                         ← Exercícios práticos
│
├── JAVASCRIPT-4/                      ← Projecto 4 — Arrays e Métodos
│   ├── README.md
│   └── DIA 3/
│
├── JAVASCRIPT-5/                      ← Projecto 5 — Funções
│   ├── README.md
│   └── DIA 4/
│
├── JAVASCRIPT-6/                      ← Projecto 6 — Objetos e JSON
│   ├── README.md
│   └── DIA 4/
│
├── JAVASCRIPT-7/                      ← Projecto 7 — Manipulação do DOM
│   ├── README.md
│   └── DIA 4/
│
├── JAVASCRIPT-8/                      ← Projecto 8 — Eventos
│   ├── README.md
│   └── index.html
│
├── JAVASCRIPT-9/                      ← Projecto 9 — Lista de Tarefas
│   ├── README.md
│   └── index.html                     ← Aplicação completa
│
├── JAVASCRIPT-10/                     ← Projecto 10 — Galeria de Imagens
│   ├── README.md
│   └── index.html                     ← Aplicação completa
│
└── Manipula-o-de-DOM-e-DocumentFragment/  ← Extra — DOM Avançado
    ├── README.md
    ├── index1.html                    ← Abordagem sem optimização
    ├── index2.html                    ← Abordagem com innerHTML
    └── index3.html                    ← Abordagem com DocumentFragment
```

---

## Todos os Projectos

### 🔰 Fundamentos

| # | Projecto | Conceitos | Artefactos |
|---|----------|-----------|------------|
| 1 | [**JAVASCRIPT**](./JAVASCRIPT/) | `var`/`let`/`const`, tipos primitivos, `console.log`, `alert`, `prompt` | DIA1, DIA 1 2.0 |
| 2 | [**JAVASCRIPT-2**](./JAVASCRIPT-2/) | Operadores (`+`, `-`, `%`, `===`, `!==`), condicionais (`if`/`else`/`switch`) | `index.html` |
| 3 | [**JAVASCRIPT-3**](./JAVASCRIPT-3/) | Laços (`for`, `while`, `do-while`), `break`/`continue`, contadores | DIA 2 |

### 🟡 Estruturas de Dados e Funções

| # | Projecto | Conceitos | Artefactos |
|---|----------|-----------|------------|
| 4 | [**JAVASCRIPT-4**](./JAVASCRIPT-4/) | Arrays, índices, `.push()`, `.pop()`, `.map()`, `.filter()`, `.reduce()` | DIA 3 |
| 5 | [**JAVASCRIPT-5**](./JAVASCRIPT-5/) | Funções declaradas, expressão, arrow, parâmetros, `return`, scope | DIA 4 |
| 6 | [**JAVASCRIPT-6**](./JAVASCRIPT-6/) | Objectos literais, `this`, JSON (`parse`/`stringify`), propriedades aninhadas | DIA 4 |

### 🟢 DOM e Eventos

| # | Projecto | Conceitos | Artefactos |
|---|----------|-----------|------------|
| 7 | [**JAVASCRIPT-7**](./JAVASCRIPT-7/) | `querySelector`, `createElement`, `innerHTML`, `classList`, `style` | DIA 4 |
| 8 | [**JAVASCRIPT-8**](./JAVASCRIPT-8/) | `addEventListener`, `click`, `submit`, `keydown`, delegação de eventos | `index.html` |

### 🔵 Projectos Práticos

| # | Projecto | Descrição | Funcionalidades |
|---|----------|-----------|-----------------|
| 9 | [**JAVASCRIPT-9**](./JAVASCRIPT-9/) | **Lista de Tarefas** | Criar, ler, editar, excluir, marcar concluída, persistir no `localStorage` |
| 10 | [**JAVASCRIPT-10**](./JAVASCRIPT-10/) | **Galeria de Imagens** | Grid responsivo, lightbox com navegação, filtros por categoria |

### 🟣 Extra — Performance

| # | Projecto | Conceito | Artefactos |
|---|----------|----------|------------|
| 11 | [**DOM e DocumentFragment**](./Manipula-o-de-DOM-e-DocumentFragment/) | `DocumentFragment` vs `innerHTML` vs múltiplos `appendChild` | 3 versões comparativas |

---

## Stack Tecnológica

| Camada | Tecnologia | Uso |
|--------|-----------|-----|
| Linguagem | JavaScript ES6+ | Toda a lógica dos projectos |
| Marcação | HTML5 | Estrutura das páginas e formulários |
| Estilização | CSS3 | Layout, cores, responsividade |
| Armazenamento | `localStorage` API | Persistência de dados no navegador |
| Ambiente | Navegador (Chrome/Firefox) | Execução — zero dependências |
| Ferramentas | VS Code, Git, GitHub | Edição, versionamento e publicação |

---

## Boas Práticas Aplicadas

| Prática | Onde se aplica |
|---------|----------------|
| **Nomes descritivos** | Variáveis e funções com nomes claros em português (`adicionarTarefa`, `listaDeCompras`) |
| **Código comentado** | Cada bloco de lógica tem comentários explicativos |
| **Separação de responsabilidades** | HTML (estrutura), CSS (estilo), JS (comportamento) em ficheiros ou secções distintas |
| **`const` por padrão** | Uso de `const` sempre que o valor não é reassinalado; `let` apenas quando necessário |
| **Arrow functions** | Para callbacks curtos e funções anónimas |
| **Template literals** | `` `Olá ${nome}` `` em vez de concatenação com `+` |
| **Event delegation** | Um único listener no elemento pai em vez de múltiplos listeners em cada filho |
| **DocumentFragment** | Optimização de performance ao inserir muitos elementos no DOM de uma só vez |
| **JSON para dados** | Estruturação de dados em JSON para `localStorage` |

---

## Métricas de Aprendizagem

| Métrica | Valor |
|---------|-------|
| Projectos concluídos | 11/11 |
| Conceitos cobertos | 25+ |
| Ficheiros `.html` com exemplos | 15+ |
| READMEs documentados | 12 (1 geral + 11 por projecto) |
| Linhas de código JavaScript | ~2000+ |
| Semanas de curso | ~10 |
| Nível máximo atingido | Intermediário (DOM + localStorage + CRUD) |

---

## Como Usar Esta Categoria para Estudar

### Pré-requisitos
- Navegador web (Chrome, Firefox, Edge — qualquer um)
- Editor de código (VS Code recomendado)
- **Zero instalações** — não precisa de Node.js, npm, nem servidor

### Passo a passo

1. **Começa pelo Projecto 1** — lê o README, abre os ficheiros `.html` no navegador
2. **Vê o código e o resultado** — para cada projecto, analisa o JavaScript e observa o que acontece no navegador (abre a DevTools com F12)
3. **Experimenta modificar** — altera valores, acrescenta condições, quebra de propósito e vê o que acontece
4. **Avança em ordem** — cada projecto assume que dominaste o anterior
5. **Faz os projectos práticos sem olhar o código final** — tenta implementar a Lista de Tarefas e a Galeria sozinho, usando o código dos projectos anteriores como referência

### Estrutura de cada projecto

Cada subpasta contém:
- **`README.md`** — objectivos, conceitos ensinados, explicação do código
- **`index.html`** (ou subpastas) — exemplos executáveis com HTML + CSS + JS integrados
- **Código comentado** — cada linha relevante tem um comentário a explicar o que faz

---

## Roadmap — O que vem a seguir?

| Meta | Estado |
|------|--------|
| Fundamentos (variáveis, tipos, condicionais) | ✅ Concluído |
| Laços e iterações | ✅ Concluído |
| Arrays e métodos funcionais | ✅ Concluído |
| Funções e scope | ✅ Concluído |
| Objetos e JSON | ✅ Concluído |
| Manipulação do DOM | ✅ Concluído |
| Eventos e interacção com utilizador | ✅ Concluído |
| CRUD com localStorage | ✅ Concluído |
| Galeria de Imagens interactiva | ✅ Concluído |
| DocumentFragment e performance | ✅ Concluído |
| `fetch` API e `async`/`await` | 🔜 Planeado (JavaScript Avançado) |
| Módulos ES6 (`import`/`export`) | 🔜 Planeado |
| Testes unitários com Jest | 🔜 Planeado |
| TypeScript | 🔜 Noutra categoria |

> Os tópicos avançados (fetch, módulos, testes) serão abordados em categorias separadas dentro do repositório.

---

## 📊 Progressão Visual

```
Semana 1–3   ████░░░░░░  Fundamentos (variáveis, operadores, condicionais, laços)
Semana 4–6   ██████░░░░  Estruturas (arrays, funções, objectos, JSON)
Semana 7–8   ████████░░  Browser (DOM, eventos, formulários)
Semana 9–10  ██████████  Projectos práticos (lista de tarefas, galeria, optimização)
```

---

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

