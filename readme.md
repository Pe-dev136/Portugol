# Portugol

Repositório com exemplos básicos de algoritmos e estruturas de controle em Portugol (VisualG), focado em aprendizagem de lógica de programação.

## Objetivo

Este projeto reúne pequenos programas de estudo para praticar conceitos fundamentais da linguagem Portugol, como:

- entrada e saída de dados
- variáveis e tipos
- estruturas de decisão (`se`, `escolha`)
- laços de repetição (`para`, `enquanto`)
- operadores lógicos
- funções e rotinas com retorno

## Estrutura do repositório

- `Primeiro Programa.visualg` — exemplo de menu com `escolha` e `caso`
- `Primeiro Programa (1).visualg` — exemplo de acumulador usando `para`
- `Portugol - Para.visualg` — contagem simples com laço `para`
- `Portugol - Função.visualg` — função com retorno para somar valores
- `Operadores Lógicos.visualg` — uso de `E`, `OU`, `NAO` e comparações

## Como executar

1. Instale o VisualG em seu computador.
2. Abra qualquer arquivo com extensão `.visualg`.
3. Execute o algoritmo com a opção de rodar/compilar no editor.
4. Observe a saída no console.

## Conceitos praticados

### 1. Estruturas de decisão
Exemplos de uso de `escolha` e `caso` para decidir ações com base em uma opção do usuário.

### 2. Laços de repetição
Uso do comando `para` para repetir blocos de instruções, como contagens e iterações.

### 3. Operadores lógicos
Comparações e condições combinadas com `E`, `OU` e `NAO`.

### 4. Funções
Criação de rotinas reutilizáveis com `funcao` e `retorne`.

## Exemplo de código

```text
algoritmo "MenuPetisqueira"

var
   opcao: inteiro

inicio
   escreval("1 - Camarão | 2 - Marisco | 3 - Lagosta")
   leia opcao

   escolha opcao
      caso 1
         escreval("Preparando Camarão")
      caso 2
         escreval("Preparando Marisco")
      caso 3
         escreval("Preparando Lagosta")
   fimescolha

fimalgoritmo