# Algoritmos de Ordenação em Java

Este projeto consiste em uma implementação didática e centralizada dos cinco principais algoritmos de ordenação de estruturas de dados. O objetivo é servir como guia de estudos e roteiro prático para apresentações acadêmicas ou técnicas.

## 🚀 Algoritmos Implementados

1. **Bubble Sort (Ordenação por Bolha):** Algoritmo simples que flutua os maiores elementos para o fim comparando vizinhos adjacentes.
2. **Insertion Sort (Ordenação por Inserção):** Constrói a sublista ordenada elemento por elemento, simulando a organização de cartas na mão.
3. **Quick Sort:** Método eficiente baseado em "Dividir e Conquistar" que utiliza um elemento pivô para particionar o vetor.
4. **Merge Sort (Ordenação por Mistura):** Divide o vetor consecutivamente até unidades isoladas e realiza a fusão combinada de forma ordenada.
5. **Heap Sort:** Utiliza a estrutura de dados Heap (árvore binária) para isolar o maior elemento na raiz e ordená-lo sequencialmente.

---

## 🛠️ Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina:
* [Java JDK](https://oracle.com) (versão 8 ou superior).
* Um terminal de linha de comando (Prompt de Comando, PowerShell, Terminal do Linux/Mac) ou uma IDE de sua preferência (VS Code, IntelliJ, Eclipse).

---

## 💻 Como Executar o Projeto

Siga os passos abaixo no seu terminal para compilar e rodar o arquivo principal de testes:

### 1. Clonar ou Acessar a Pasta
Navegue via terminal até o diretório onde o arquivo `Main.java` está localizado:
```bash
cd /caminho/do/seu/projeto
```

### 2. Compilar o Código
Execute o compilador do Java para gerar o arquivo `.class`:
```bash
javac Main.java
```

### 3. Executar o Programa
Rode a aplicação para visualizar a ordenação no terminal:
```bash
java Main
```

---

## 📊 Análise de Complexidade de Tempo

| Algoritmo | Melhor Caso | Caso Médio | Pior Caso |
| :--- | :---: | :---: | :---: |
| **Bubble Sort** | O(n) | O(n²) | O(n²) |
| **Insertion Sort** | O(n) | O(n²) | O(n²) |
| **Quick Sort** | O(n log n) | O(n log n) | O(n²) |
| **Merge Sort** | O(n log n) | O(n log n) | O(n log n) |
| **Heap Sort** | O(n log n) | O(n log n) | O(n log n) |

---

## 📝 Estrutura do Código

Os algoritmos foram centralizados dentro da classe principal `Main.java` como métodos estáticos. Isso evita erros de visibilidade de pacotes e facilita a execução direta em ambientes de terminal puros.

Cada método trabalha com uma cópia independente (`.clone()`) do vetor original desordenado para garantir a neutralidade dos testes.
