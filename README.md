Jogo do Número Secreto

Descrição

Este é um jogo simples onde o jogador deve adivinhar um número secreto gerado aleatoriamente entre 1 e 10. O jogo fornece dicas para ajudar o jogador a encontrar o número correto e exibe mensagens na tela utilizando síntese de voz.

Funcionalidades

Gera um número secreto aleatório entre 1 e 10.

Permite que o jogador insira palpites.

Fornece dicas se o palpite for maior ou menor que o número secreto.

Informa quando o jogador acerta o número secreto e quantas tentativas foram necessárias.

Possui um botão para reiniciar o jogo.

Tecnologias Utilizadas

HTML

CSS

JavaScript

Biblioteca ResponsiveVoice para síntese de voz.

Como Jogar

O jogo exibe uma mensagem inicial pedindo para o jogador escolher um número entre 1 e 10.

O jogador digita um número no campo de entrada e pressiona o botão de verificação.

O jogo informa se o palpite é maior ou menor que o número secreto.

Quando o jogador acerta, o jogo exibe uma mensagem de sucesso e a quantidade de tentativas utilizadas.

O jogador pode reiniciar o jogo clicando no botão de reiniciar.

Estrutura do Código

exibirTextoNaTela(tag, texto): Exibe uma mensagem na tela e a reproduz em voz alta.

exibirMensagemInicial(): Exibe a mensagem inicial do jogo.

verificarChute(): Verifica se o chute do jogador é correto e fornece dicas caso não seja.

gerarNumeroAleatorio(): Gera um número aleatório e evita repetições até que todos os números tenham sido utilizados.

limparCampo(): Limpa o campo de entrada do jogador.

reiniciarJogo(): Reinicia o jogo gerando um novo número secreto e resetando as tentativas.

Requisitos

Para rodar o jogo, é necessário um navegador moderno com suporte a JavaScript e acesso à biblioteca ResponsiveVoice para a síntese de voz.

Exemplo de Uso

Abra o arquivo HTML no navegador e comece a jogar digitando um número e pressionando o botão de verificação.

Autor

Victor Magno - Desenvolvido como um exercício de programação em JavaScript.

Licença

Este projeto é de livre uso e pode ser modificado conforme necessário.
