# AgeChecker

- O código é acionado pela função "verificar()", que realiza as seguintes etapas:

1. Obtém a data atual usando "new Date()" e armazena o ano atual em uma variável chamada "ano".

2. Captura o valor inserido em um campo de entrada (input) HTML com o ID "txtano" e armazena-o na variável "fano".

3. Define um local na página HTML onde a resposta da verificação será exibida, usando o seletor "section#res" e armazenando-o na variável "res".

4. Verifica se o campo de entrada "fano" está vazio ou contém um valor maior que o ano atual. Se a condição for verdadeira, um alerta de erro é exibido.

5. Identifica o botão de opção (radio button) selecionado, indicando o gênero da pessoa (masculino ou feminino).

6. Calcula a idade da pessoa a partir do valor inserido no campo de entrada e o ano atual.

7. Com base no gênero e na faixa etária, seleciona uma imagem representativa e a exibe no resultado.
