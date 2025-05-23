# Mario Kart - Corrida de Dados 🚗🎲

Bem-vindo ao mini-game de corrida inspirado em Mario Kart, feito em Node.js! Escolha dois personagens e veja quem vence uma corrida de 5 rodadas, onde cada trecho da pista testa um atributo diferente dos competidores.

---

## 👾 Personagens Disponíveis

| Personagem    | Velocidade | Manobrabilidade | Poder |
|:-------------:|:----------:|:---------------:|:-----:|
| 1-Mario         |     4      |        3        |   2   |
| 2-Luigi         |     3      |        4        |   1   |
| 3-Yoshi         |     2      |        5        |   2   |
| 4-Bowser        |     5      |        2        |   3   |
| 5-Peach         |     5      |        5        |   1   |
| 6-Donkey Kong   |     1      |        5        |   2   |

---

## 🏁 Como Jogar

1. Execute o projeto com Node.js.
2. Escolha dois personagens no terminal.
3. Acompanhe a corrida rodada a rodada!

---

## 🎲 Regras do Jogo

- A corrida tem 5 rodadas.
- Em cada rodada, sorteia-se o tipo de trecho:
    - **RETA**: Soma-se o valor do dado ao atributo VELOCIDADE.
    - **CURVA**: Soma-se o valor do dado ao atributo MANOBRABILIDADE.
    - **CONFRONTO**: Soma-se o valor do dado ao atributo PODER. Quem perde, perde 1 ponto (se tiver).
- O vencedor da rodada ganha 1 ponto.
- Não é permitido pontuação negativa.
- Vence quem tiver mais pontos ao final das 5 rodadas.

---

## 🚀 Como Executar

1. Tenha o Node.js instalado.
2. Salve o código em um arquivo, por exemplo, `kart.js`.
3. No terminal, execute:

   ```bash
   node kart.js
   ```

4. Siga as instruções na tela para escolher os personagens e acompanhar a disputa!

---

## 💡 Personalize!

- Adicione mais personagens ou modifique atributos para criar desafios diferentes.
- Use sua criatividade para criar novas regras de pista!

---

Feito para fins educativos e diversão!  
Divirta-se 🚦🏆