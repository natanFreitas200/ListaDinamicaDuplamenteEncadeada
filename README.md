# Lista Dinâmica Duplamente Encadeada

## Descrição

Este projeto implementa uma estrutura de dados de Lista Dinâmica Duplamente Encadeada em Java. Uma lista duplamente encadeada é uma estrutura de dados linear onde cada elemento (nó) contém dados e duas referências: uma para o próximo nó e outra para o nó anterior.

## Características

- **Inserção**: Permite inserir elementos no início, fim ou em qualquer posição específica
- **Remoção**: Remove elementos por valor ou posição
- **Busca**: Localiza elementos na lista
- **Navegação Bidirecional**: Permite percorrer a lista tanto para frente quanto para trás
- **Gestão Dinâmica de Memória**: Aloca e desaloca memória conforme necessário

## Estrutura do Projeto

```
ListaDinamicaDuplamenteEncadeada/
├── src/
│   └── Main.java
├── README.md
└── ListaDinamicaDuplamenteEncadeada.iml
```

## Vantagens da Lista Duplamente Encadeada

- Inserção e remoção em O(1) quando se tem referência ao nó
- Navegação bidirecional eficiente
- Não requer tamanho fixo predefinido
- Facilita operações como inversão da lista

## Desvantagens

- Maior uso de memória devido ao ponteiro adicional
- Complexidade adicional na implementação
- Acesso sequencial (não há acesso direto por índice)

## Como Executar

1. Certifique-se de ter o Java instalado (versão 8 ou superior)
2. Compile o projeto:
   ```bash
   javac src/Main.java
   ```
3. Execute:
   ```bash
   java -cp src Main
   ```

## Operações Principais

### Inserção
- Inserir no início
- Inserir no final
- Inserir em posição específica

### Remoção
- Remover do início
- Remover do final
- Remover por valor
- Remover por posição

### Busca e Navegação
- Buscar elemento
- Percorrer lista (frente e verso)
- Verificar se lista está vazia
- Obter tamanho da lista

## Complexidade Temporal

| Operação | Complexidade |
|----------|--------------|
| Inserção no início/fim | O(1) |
| Inserção no meio | O(n) |
| Remoção no início/fim | O(1) |
| Remoção no meio | O(n) |
| Busca | O(n) |
| Acesso por índice | O(n) |

## Tecnologias Utilizadas

- Java
- Paradigma de Programação Orientada a Objetos

## Contribuição

Este projeto é uma implementação educacional de estrutura de dados. Contribuições para melhorias e otimizações são bem-vindas.

