# Tabuleiro da Velha

Este repositório é para o exercício do professor: jogar **jogo da velha** com um amigo usando o **Git**.

---

## Objetivo

- Jogar jogo da velha em um arquivo de texto (`tabuleiro.txt`).  
- Praticar Git enviando e recebendo jogadas.  

---

## Como jogar

1. **Quem vai jogar**:  
   - Abrir o arquivo `tabuleiro.txt`.  
   - Escolher uma posição e colocar seu símbolo (X ou O).  
   - Trocar a linha `Vez do jogador` para o outro jogador.  
   - Salvar o arquivo.

2. **Enviar a jogada**:
   ```bash
   git add tabuleiro.txt
   git commit -m "Minha jogada"
   git push
