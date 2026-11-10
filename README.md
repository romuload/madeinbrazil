# Made in Brazil

Protótipo de jogo para aprender expressões em inglês a partir das expressões brasileiras, com as frases do livro *Made in Brazil*, de José Carlos Pereira Teixeira.

**Jogar:** https://romuload.github.io/madeinbrazil/

## Os quatro jogos

- **Ao pé da letra.** A expressão brasileira aparece traduzida palavra por palavra ("I paid the duck") e a pessoa escolhe como um americano diz a mesma coisa. Cada acerto vira uma figurinha no álbum: 114 no total, entre comuns, raras e lendárias.
- **Viagem.** A pessoa desembarca nos Estados Unidos e passa por seis paradas (aeroporto, rua, hotel, restaurante, compras e imprevistos), com seis situações em cada uma. Quatro acertos carimbam a parada no passaporte e liberam a seguinte.
- **Treino.** As 2.849 frases da parte português-inglês do livro, em rodadas de 10, sorteadas do livro todo ou de uma letra. Aparece a frase em português e a pessoa escolhe a tradução.
- **Caça-palavras.** Doze expressões em inglês escondidas numa grade, em oito direções, com cinco minutos no relógio. A lista dá a dica em português e revela a tradução quando a pessoa acha a palavra.

Também há expressão do dia, sequência de dias jogados, rodadas por tema e um resultado pronto para compartilhar.

## Como funciona

O jogo é um único arquivo, `index.html`, sem etapa de build e sem servidor. O progresso (álbum, carimbos, frases treinadas, recordes e sequência) fica salvo no navegador de quem joga.

Para rodar no computador, abra o `index.html` no navegador.

## Pendências conhecidas

- O botão de ouvir usa a voz do próprio aparelho, e a qualidade varia. A ideia é trocar por áudio gravado.
- As traduções literais e as situações do modo Viagem foram escritas para o jogo e ainda precisam de revisão.
- As frases do Treino e do Caça-palavras foram extraídas do PDF do livro por programa e conferidas só por amostragem.

## Créditos e direitos

- **Frases:** livro *Made in Brazil*, © 2024 José Carlos Pereira Teixeira. Todos os direitos reservados ao autor; este repositório não concede licença sobre esse conteúdo.
- **Ícones:** [Kubai Icons](https://github.com/kubai087/kubai-icons), licença MIT. O aviso de direitos está em `LICENSE-KUBAI-ICONS`.
- **Fonte:** Nunito, carregada do Google Fonts (SIL Open Font License).
- **Visual:** formas e cores seguem um guia de design inspirado no Duolingo. Este projeto não tem vínculo com o Duolingo.
