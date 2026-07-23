# Python Fundamentos

Este módulo reúne os fundamentos de Python que servirão como base para o restante da trilha de Engenharia de Dados.

O objetivo não é apenas aprender a sintaxe da linguagem, mas compreender o modelo mental utilizado pelo Python para representar e manipular objetos.

---

# Conteúdo estudado

## Semana 1 — Dia 1

### Conceitos

- Variáveis
- Objetos
- Referências
- Tipos de dados (`str` e `int`)
- Funções
- Métodos
- Ordem de execução das funções
- Introdução à Programação Orientada a Objetos (POO)

### Métodos estudados

- `print()`
- `type()`
- `upper()`

### Principais aprendizados

- Variáveis apontam para objetos.
- Objetos possuem comportamentos (métodos).
- O ponto (`.`) acessa algo pertencente ao objeto.
- Os parênteses (`()`) executam uma função ou método.
- `upper()` retorna um novo objeto sem alterar automaticamente o original.
- O Python resolve expressões de dentro para fora.

---

## Semana 1 — Dia 2

### Conceitos

- Listas (`list`)
- Coleções de objetos
- Índices
- Acesso por posição
- Manipulação de listas

### Métodos estudados

- `append()`

### Sintaxe estudada

```python
frutas[indice]
```

### Principais aprendizados

- Uma lista também é um objeto.
- Uma lista organiza outros objetos em uma sequência ordenada.
- Os índices começam em `0`.
- `append()` adiciona um elemento ao final da lista.
- `print(lista)` imprime a coleção inteira.
- `print(lista[indice])` imprime apenas o elemento daquela posição.
- A variável continua apontando para a mesma lista após o uso de `append()`.

---

# Estrutura atual

```
Python Fundamentos/
│
├── README.md
├── main.py
└── .gitignore
```

---

# Objetivo do módulo

Ao final deste módulo, pretendo dominar os fundamentos da linguagem Python para utilizá-la posteriormente em:

- Manipulação de arquivos
- SQL com Python
- APIs
- Pandas
- ETL
- PySpark
- Engenharia de Dados

---

# Próximos tópicos

- Métodos de listas (`insert`, `remove`, `pop`)
- `len()`
- Listas heterogêneas
- Dicionários (`dict`)
- Condicionais
- Laços de repetição
- Funções