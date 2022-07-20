# Fonte de Tensão ajustável 
# Diagrama do circuito
![alt text](https://github.com/joaoserpellone/Fonte-tens-o-ajust-vel/blob/main/circuitoFonteFalstad.png)
[Link para o circuito no falstad](https://tinyurl.com/25pmmmge)

# Lista de compontentes:
  * Transformador: componente que é utilizado para reduzir a corrente vinda da tomada (127v em média) para valores mais baixos, em torno de 24v.
  * Ponte de diodo: utilizando-se 4 diodos (1N4007), fizemos um "cruzamento entre eles". Isso é necessário para mudar a fase negativa da corrente alternada e torná-la sempre positiva.
  * Capacitor: acumula tensão na fase de aumento da tensão interna do circuito e, na fase de diminuição libera a ddp acumulada para o circuito.
  * Resistor: há três resistores utilizados no circuito, o primeiro de 2k (no circuito real ligamos dois de 1k em série) para reduzir a corrente que passa pelo led, o segundo de 1k após o capacitor, que reduz a tensão vinda de aproximadamente 24v para em torno de 13v. O segundo, de 5k, se faz necessário para reduzir a corrente para 100mA na parte do componente a ser alimentado.
  * Diodo Zenner: regula a tensão máxima, caso a tensão vinda seja maior que a tensão do diodo, ele permite e apassagem de corrente e diminui até os 12v desejados, no nosso caso utilizamos o de 13v no circuito prático.
  * Potenciometro: dispositivo que permite mudar a resistência interna dele mesmo e consequentemente ajustar a tensão entre 12v (máximo) e 3v (mínimo).
  * Transistor: permite a passagem de corrente desejada (100ma) anterior ao potenciometro.

## Componentes escolhidos:


| Qtd | Componente       | Preço  |
| --- |:----------------:| ------:|
| 4   | Diodo 1N4007     | R$ 0,20|
| 1   | Capacitor 470uF  | R$ 1,05|
| 3   | Resistor 1k      | R$ 0,21|
| 1   | Resistor 5k      | R$ 0,07|
| 1   | Diodo Zenner(13v)| R$ 0,50|
| 1   | Potenciometro 10k| R$ 4,75|
| 1   | Tranistor 2N3904 | R$ 0,40|
| Total|                 | R$ 7,13|

# Circuito esquemático no EAGLE
![alt text](https://github.com/joaoserpellone/Fonte-tens-o-ajust-vel/blob/main/eagleEsquematico.png)

# Circuito PCB no EAGLE 
![alt text](https://github.com/joaoserpellone/Fonte-tens-o-ajust-vel/blob/main/circuitoEaglePCB.png)
