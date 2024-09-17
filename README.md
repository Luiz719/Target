
# Desafio de Programação

Este repositório contém soluções para as questões apresentadas em um processo seletivo de programação.

## Questões

### 1. Qual será o valor da variável `SOMA` ao final do processamento?

**Enunciado**:  
Dado o seguinte trecho de código:
```c
int INDICE = 13, SOMA = 0, K = 0;
Enquanto K < INDICE faça { 
    K = K + 1; 
    SOMA = SOMA + K; 
}
Imprimir(SOMA);
```
Qual será o valor de `SOMA` ao final?

**Resposta**:  
Dado que:
```
SOMA = 1 + 2 + 3 + ... + 13 
```
Pela Soma dos 13 termos da PA, tem-se que:
$$ SOMA =  \frac{(1+13) \cdot 13}{2} = 91 $$ 
Logo, o valor final de `SOMA` será **91**.

A versão em código também pode ser encontra em: [Código da questão 1](questão1.py)

---

### 2. Verificação de número na sequência de Fibonacci

**Enunciado**:  
Escreva um programa que calcule a sequência de Fibonacci e retorne se um número informado pertence ou não à sequência.

[Ver código da questão 2](questão2.py)

---

### 3. Análise do faturamento diário

**Enunciado**:  
Dado um vetor que guarda o valor de faturamento diário de uma distribuidora, calcule:
- O menor valor de faturamento ocorrido em um dia do mês;
- O maior valor de faturamento ocorrido em um dia do mês;
- Número de dias no mês em que o valor de faturamento diário foi superior à média mensal.

[Ver código da questão 3](questão3.py)

---

### 4. Percentual de faturamento por estado

**Enunciado**:  
Dado o valor de faturamento mensal de uma distribuidora detalhado por estado, calcule o percentual de representação de cada estado no valor total mensal.

[Ver código da questão 4](questão4.py)

---

### 5. Inversão de string

**Enunciado**:  
Escreva um programa que inverta os caracteres de uma string sem utilizar funções prontas como `reverse()`.

[Ver código da questão 5](questão5.py)

---

## Tecnologias Utilizadas

- **Linguagem**: Python
- **Formato de dados**: JSON
