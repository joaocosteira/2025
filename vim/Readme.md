# Vim

Basicamente vamos usar isto para aprender a usar Vim

## Links

- https://www.youtube.com/watch?v=X6AR2RMB5tE&list=PLm323Lc7iSW_wuxqmKx_xxNtJC_hJbQ7R

# [First Video](https://www.youtube.com/watch?v=X6AR2RMB5tE&list=PLm323Lc7iSW_wuxqmKx_xxNtJC_hJbQ7R)

Temos basicamente uma separacao, ok, existe o vim editor, ou seja o programa e editior e temos as vim motions, que sao basicamente os shortcuts que estamos a ver e a aprender

O vim e um **modal editor** que basicamente significa que temos um conjunto de modos e podemos alterar entre eles

Modos Disponiveis:

## Normal Mode

O de quando clicamos no escape
Mover o cursor:

- **j** para baixo
- **k** para cima
- **h** para esq
- **l** para dir
- **w** move by word
- **b** para tras, o oposto do w
- **v** comeca basicamente a fazer o highlight da pavara e do que vem depois
- **a** entra em insert mode mas no fim da palavra

### Command Count Motion

O que queremos dizer com isto: basicamente podemos combinar os comnados de modo a fazer mais que uma acao de uma vez.
Por exemplo estamos a tratar das coisas de movimento, ou seja motion, temos o botao de j,k,l, etc.
Mas ja vimos que mesmo ao lado temos a palavra count, que significa quantas vezes queremos aplicar essa acao.

Exemplo mais concreto: sabemos que a tecla k move para cima, se entao aplicarmos o combo **3k** basicamente vamos subir 3 linhas em relacao a atual.
De forma analoga temos a questao de combinar comandos, por exemplo sabemos que v faz a selecao, o w da para saltar a palavra e o d de delete, logo podemos aplicar o combo **vwd** para apagar uma palavra.

# Delete

- apaga o caracter atual

* **dd** apagar a linha atual
* **u** faz o undo da deletion (basicamente control z)

## Insert Mode

mode de insercacao, quando clicamos no i

## Visual Mode

Quando estamos neste modo podemos selecionar coisas e assim, estando no modo normal basta clicar em v
Podemos pensar que este modo e basicamente um modo em que podemos andar com os mesmos shortcuts e

- **y** basicamente faz copy do que estiver selecionado
- **p** paste do que tiver sido copiado, mas copia apenas literalmente o que foi selecionado, e muito normal num editor normal ao selecionar uma linha tambem incluir o new line mas aqui nao acontece isso.

Como alternativa podemos entrar ao clicar em **shift y** no modo **Visual Line** e desta maneira ao faze o copy trata mesmo da linha

## Command Mode

o modo de comando e o dos **:**) onde pontro podemos escrever comandos e afins. Funciona ao clicar em : apartir do normal mode
Exemplo de comandos:

- :w para escrever em ficheiro\
- :q para fechar o vim
