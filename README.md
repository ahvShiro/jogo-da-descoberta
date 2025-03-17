# Jogo da descoberta

Este é um projeto que foi desenvolvido em sala de aula, na matéria de Algoritmos e Estruturas de Dados II. Neste jogo, o objetivo é adivinhar uma palavra a partir de seu anagrama.

## Como funciona

1. Uma palavra é aleatoriamente selecionada a partir de uma lista de palavras pré-determinada
2. A palavra é escolhida e exibida na tela
3. O usuário tenta adivinhar a palavra, digitando-a no console
4. Se for a palavra certa, uma mensagem aparece na tela e ele ganha o jogo
5. Se não, o jogo continua rodando até o usuário acertar ou desistir
6. É possível pedir uma dica da primeira e da última letra da palavra, digitando `!d`
7. E para sair do jogo, o usuário pode digitar `!q`, encerrando o loop e terminando o jogo

## Rodando o jogo

```bash
javac Main.java
```

## Termos chave aprendidos com esse projeto

- Leitura de entradas de console com Scanner
- Uso de loops e condicionais
- Manipulação de strings e chars

## Perspectiva para futuros projetos

- Esse projeto me lembrou muito o Wordle, ou Termo, onde você adivinha palavras e ganha dicas a cada tentativa. Talvez eu tente recriar esse tipo de jogo em Java, com uma interface CLI decente
- Talvez futuramente eu possa utilizar dicionários externos para extrair uma palavra aleatória do jogo
- Uma coisa interessante a se pensar seria como implementar um sistema de persistência de dados em Java
