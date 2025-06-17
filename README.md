# Coding Essentials - Logic Building for Beginners

Este repositório contém anotações, explicações e códigos desenvolvidos durante o curso **Coding Essentials - Logic Building for Beginners** da Udemy.

---

## Aula: Soma dos primeiros N números (Sum of first N numbers)

### Descrição do problema

Dado um número natural **N**, calcule a soma dos números de 1 até N.

### Exemplo

- N = 4  
- Saída: 10 (1 + 2 + 3 + 4)

### Código em Python

```python
N = 4
soma = 0
i = 1

while i <= N:
    soma = soma + i
    i = i + 1

print(soma)
