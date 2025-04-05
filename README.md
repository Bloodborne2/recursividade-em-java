# 📘 Fatorial Recursivo em Java

## 💡 Descrição
Pequeno programa em Java que calcula o fatorial de um número informado pelo usuário utilizando recursividade. A interação é feita com `JOptionPane`.

## 🛠️ Como Funciona
O usuário digita um número. O programa usa uma função recursiva para calcular o fatorial e exibe o resultado em uma janela pop-up.

## 📎 Estrutura

### `ExFatRecursividade.java`
Lê o número com `JOptionPane`, chama o método de fatorial e exibe o resultado.

### `Fatorial.java`
Contém o método `fatorialRecursivo(int num)` que retorna `1` se `num == 0`, ou `num * fatorialRecursivo(num - 1)`.

## ✅ Exemplo

**Entrada:** 5  
**Saída:** O fatorial é: 120

## 📚 Conceitos
- Recursividade  
- Entrada/Saída com GUI (`JOptionPane`)  
- Manipulação de métodos em Java
