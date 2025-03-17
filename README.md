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

## Screenshots

Demonstração da gameplay

![image](https://github.com/user-attachments/assets/62462b5d-3acb-4156-b841-ff34ceabfdb4)

![image](https://github.com/user-attachments/assets/c8aa5521-47d1-4dd0-ab19-2c738aa21435)

---

Demonstração das opções

![image](https://github.com/user-attachments/assets/ce680921-0ded-48e6-95e1-a6907fcfe47e)

![image](https://github.com/user-attachments/assets/5c0b3326-06d6-4fd5-a9d5-5feef855a553)

## Termos chave aprendidos com esse projeto

- Leitura de entradas de console com Scanner
- Uso de loops e condicionais
- Manipulação de strings e chars

## Perspectiva para futuros projetos

- Esse projeto me lembrou muito o Wordle, ou Termo, onde você adivinha palavras e ganha dicas a cada tentativa. Talvez eu tente recriar esse tipo de jogo em Java, com uma interface CLI decente
- Talvez futuramente eu possa utilizar dicionários externos para extrair uma palavra aleatória do jogo
- Uma coisa interessante a se pensar seria como implementar um sistema de persistência de dados em Java
