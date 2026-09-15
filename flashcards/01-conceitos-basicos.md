# Conceitos Básicos de Programação

## 1. O que é uma variável?
**Resposta:** Uma variável é um espaço na memória do computador que armazena um valor. Ela tem um nome e um tipo de dado.

---

## 2. Qual é a diferença entre `let`, `const` e `var` em JavaScript?
**Resposta:** 
- `var`: Escopo global ou de função, pode ser redeclarada
- `let`: Escopo de bloco, não pode ser redeclarada
- `const`: Escopo de bloco, não pode ser redeclarada nem alterada (imutável)

---

## 3. O que é um tipo de dado primitivo?
**Resposta:** São os tipos de dados básicos de uma linguagem: números, strings, booleanos, null, undefined, symbols (em JS).

---

## 4. Como funciona a passagem por valor vs passagem por referência?
**Resposta:**
- **Passagem por valor:** A função recebe uma cópia do valor
- **Passagem por referência:** A função recebe o endereço de memória do objeto

---

## 5. O que é escopo de variável?
**Resposta:** É a região do código onde uma variável pode ser acessada. Pode ser global, local, de bloco, ou de função.

---

## 6. O que é uma função?
**Resposta:** É um bloco de código reutilizável que realiza uma tarefa específica. Pode receber parâmetros e retornar valores.

---

## 7. Qual é a diferença entre `==` e `===` em JavaScript?
**Resposta:**
- `==`: Comparação com coerção de tipo (5 == "5" é true)
- `===`: Comparação sem coerção (5 === "5" é false)

---

## 8. O que é hoisting em JavaScript?
**Resposta:** É o comportamento onde declarações de `var`, funções e `function` são movidas para o topo do escopo antes da execução.

---

## 9. O que é uma callback function?
**Resposta:** É uma função passada como argumento para outra função, que será executada em um momento específico (geralmente após uma operação assíncrona).

---

## 10. O que é uma closure?
**Resposta:** É uma função que captura variáveis do escopo externo e as mantém acessíveis mesmo após a função externa ter sido executada.
