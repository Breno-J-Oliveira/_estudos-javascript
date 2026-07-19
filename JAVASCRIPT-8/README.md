💜 Lição Prática — Sistema de Avaliação de Histórico de Desempenho (JavaScript Básico)
<p align="center"> <img src="https://img.shields.io/badge/status-concluído-brightgreen?style=for-the-badge" alt="Status"> <img src="https://img.shields.io/badge/versão-1.0-blue?style=for-the-badge" alt="Versão"> <img src="https://img.shields.io/badge/JS-JavaScript-F0DB4F?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"> <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"> </p>
📘 Sobre este README

Este projeto documenta uma atividade prática de manipulação de estruturas condicionais e lógica de programação em JavaScript, aplicada à criação de um sistema de avaliação de desempenho para cálculo de aumento salarial.

O objetivo foi desenvolver uma aplicação simples capaz de:

Permitir que o usuário insira dados de um funcionário
Processar regras de aumento salarial com base no cargo
Verificar critérios de elegibilidade com base em faltas
Exibir dinamicamente o resultado do cálculo
Estilizar a interface com design moderno, responsivo e organizado

🧭 Resumo da Atividade
🎯 O que faz:

O sistema permite que o usuário informe:

Categoria	Dados Informados
A. Identificação	Nome do funcionário
B. Cargo	Aprendiz, Analista de TI, Gerente de TI, Diretor de TI
C. Desempenho	Número de faltas
D. Financeiro	Salário atual

Após clicar em "Calcular Aumento", o programa:

✔️ Verifica o cargo
✔️ Aplica o percentual de aumento correspondente
✔️ Avalia se o funcionário possui faltas
✔️ Exibe o novo salário (caso tenha direito)
✔️ Ou informa a não elegibilidade ao aumento

⚙️ Funcionalidades Implementadas
✅ Entrada de Dados

Recebe informações via:

Input de texto (nome)

Select (cargo)

Input numérico (faltas)

Input numérico (salário)

Valida e converte os dados usando:

parseInt()

parseFloat()

✅ Processamento de Regras

Utiliza:

Estrutura switch para definir o percentual de aumento por cargo

Estrutura if/else para validar faltas

Operações aritméticas para cálculo do novo salário

toFixed(2) para formatação monetária

Percentuais aplicados:

Cargo	Aumento
Aprendiz	0%
Analista de TI	10%
Gerente de TI	15%
Diretor de TI	20%
✅ Interação Dinâmica

Atualiza o resultado utilizando:

document.getElementById()

innerHTML

Evento onclick

Sem necessidade de recarregar a página.

✅ Interface e Estilização

✔️ Layout dividido em formulário e painel de resultado
✔️ Design moderno com paleta roxa
✔️ Efeitos de hover no botão
✔️ Box-shadow e bordas arredondadas
✔️ Estrutura responsiva utilizando flexbox

🧠 Conceitos Trabalhados

Estruturas condicionais (if/else)
Estrutura de decisão switch
Manipulação do DOM
Conversão de dados (parseInt, parseFloat)
Operações matemáticas
Template strings
Eventos HTML (onclick)
Organização de layout com CSS
Uso de Flexbox
Estilização moderna com sombras e transições

🎯 Aprendizado Esperado

Ao final desta atividade, o aluno será capaz de:

Criar sistemas simples de regras de negócio
Aplicar lógica condicional baseada em múltiplos critérios
Manipular dados de entrada do usuário
Atualizar conteúdo HTML dinamicamente
Calcular valores com base em percentuais
Criar interfaces organizadas e estilizadas

🖥️ Estrutura do Projeto
📁 sistema-avaliacao-desempenho
├── index.html
└── README.md
🚀 Status do Projeto

✔️ Projeto finalizado
✔️ Funcionalidades implementadas
✔️ Interface estilizada
✔️ Código organizado e funcional
✔️ Cálculo correto de aumento salarial

👤 Contato
<p align="center"> <a href="https://github.com/Breno-J-Oliveira" target="_blank"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"> </a> <a href="https://www.instagram.com/brenot300" target="_blank"> <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"> </a> <a href="https://x.com/BrenoJOliveira_" target="_blank"> <img src="https://img.shields.io/badge/X-1DA1F2?style=for-the-badge&logo=x&logoColor=white"> </a> </p>
