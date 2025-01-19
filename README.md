# Insertion-Sort
 
# Implementação de Algoritmos de Ordenação com Insertion Sort

Este repositório contém dois programas em C que implementam e demonstram o funcionamento do algoritmo de ordenação **Insertion Sort**. Cada programa inclui funcionalidades específicas, além de medir o tempo de execução para avaliar a eficiência do método.

---

## Estrutura dos Arquivos

### 1. **codigo_base.c**
Este arquivo contém uma implementação completa do algoritmo Insertion Sort, com funcionalidades adicionais para diferentes tipos de ordenação e medições de desempenho.

#### **Funcionalidades:**
- **Ordenação Crescente:** Ordena o vetor em ordem crescente.
- **Ordenação Decrescente:** Ordena o vetor em ordem decrescente.
- **Metade Crescente e Metade Decrescente:** Ordena a primeira metade do vetor em ordem crescente e a segunda metade em ordem decrescente.
- **Metade Decrescente e Metade Crescente:** Ordena a primeira metade do vetor em ordem decrescente e a segunda metade em ordem crescente.
- **Vetor Aleatório:** Inicializa o vetor com valores aleatórios, utilizado para resetar o vetor entre operações.
- **Medição do Tempo de Execução:** Mede e exibe o tempo de execução para cada tipo de ordenação.

---

### 2. **codigo_com_10_interacoes.c**
Este arquivo apresenta uma versão simplificada do algoritmo com foco em ordenar o vetor e exibir os resultados de forma clara.

#### **Funcionalidades:**
- **Ordenação com Insertion Sort:** Ordena o vetor de entrada em ordem crescente utilizando o método de Insertion Sort.
- **Impressão do Array:** Exibe o vetor antes e após a ordenação para facilitar a visualização dos resultados.

---

## Como Executar
1. **Compilar o programa:**
   Para compilar os arquivos, utilize um compilador de C, como o GCC:
   ```bash
   gcc codigo_base.c -o codigo_base
   gcc codigo_com_10_interacoes.c -o codigo_com_10_interacoes


# Tabela de Comparação de Tempos para 100.000 Números

| Situação                                         | Tempo de Execução |
|-------------------------------------------------|-------------------|
| Vetor totalmente ordenado decrescentemente      | 6,05s            |
| Vetor totalmente ordenado crescentemente        | 12,05s           |
| Primeira metade ordenada crescente, segunda metade ordenada decrescentemente | 3,11s |
| Primeira metade ordenada decrescente, segunda metade ordenada crescentemente | 5,83s |
| Elementos totalmente desordenados               | 6,16s            |
