# Projeto-Fonte
O Projeto consiste em criar o circuito de uma fonte de tensão ajustável entre 3V e 12V com apacidade de 100mA usando o simulador falstad e em seguida transformar esse circuito de representação simbólica em um Projeto do Esquemático e PCB (printed circuit board) usando a ferramenta EAGLE.
## Componentes do Circuito:
+ #### Fonte de Tensão
Para alimentar o circuito será preciso liga-lo numa tomada de 110v, portanto será usado  no circuito sumilado do falstad uma fonte de tensão de corrente alternada com 2 terminais configurada com uma **Tensão Máxima** de 179.6V e uma **Frequência** de 60Hz.
+ #### Transformador
O primeiro componente do circuito é o transformador que tem como função diminuir a tensão de entrada de 127V para 15V.
+ #### Diodo
A próxima parte do circuito é a ponte de diodo que tem como função é retificar a corrente fazendo com que o semiciclo negativo fique positivo. Além disso cada diodo consome 0.7V portanto a ponte gera uma queda de tensão de 1.4V já que somente dois diodos ficam ativos de cada vez.
+ #### Capacitor
O próximo componente é o capacitor que faz a filtragem diminuindo a variação de tensão do circuito chamada de _ripple_ (diferença entre o valor do pico da variação da tensão e o valor do ponto mais baixo da variação da tensão) e deixando a tensão e a corrente mais estáveis.
+ #### Resistor
Os resistores limitam a corrente e são usados para proteger componentes que queimariam se uma corrente muito alta passasse por eles devido ao calor que seria gerado.
+ #### LED (light emitting diode)
Serve para indicar que o circuito está ligado. É um diodo que emite uma luz quando uma corrente passa por ele.
+ #### Diodo Zener
O Zener faz a função de regulagem que visa cessar a variação de tensão do circuito. É um dido com uma barreira de tensão mais baixa que deixa a corrente passar assim que receber uma tensão maior que sua barreira, que no zener desse ciruito é 13V.
+ #### Potenciômetro
É um resistor que pode variar o valor de sua resistência permitindo ajustar a tensão do circuito entre 12V e 3V.
+ #### Transistor Bipolar NPN
O transistor permite a passagem de corrente de forma ajustável.
## Tabela
Componente|Quantidade|Preço
---|---|---
[Transformador 15V](https://proesi.com.br/transformador-entrada-110-220v-saida-7-5-7-5-200ma.html)|1x|R$ 28,95
[Diodo 1N4004](https://proesi.com.br/1n4004-diodo.html)|4x|R$ 0,08
[Capacitor 470uF](https://www.baudaeletronica.com.br/capacitor-eletrolitico-470uf-35v.html)|1x|
[LED](https://proesi.com.br/led-difuso-5mm-vermelho.html)|1x|R$
[Resistor 2.2k]()|2x|R$
[Resistor 1k](https://proesi.com.br/resistor-carbono-cr25-1-4w-1k.html)|1x|R$ 0,03
[Diodo Zener 13V]()|1x|R$
[Potenciômetro 5K]()|1x|R$
[Transistor NPN]()|1x|R$


