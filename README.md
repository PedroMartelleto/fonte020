# - Projeto Fonte de Tensão entre 3V e 12V
Projeto referente a matéria de Eletrônica para Computação (SSC0180), ministrada no primeiro semestre de 2020 pelo professor Eduardo do Valle Simões, na Universidade de São Paulo, campus São Carlos. A proposta do projeto foi criar uma fonte que receberá 127V da tomada e uma corrente alternada e os transformará em uma tensão variável de 3V a 12V com capacidade de 100mA.
 
# - Integrantes do Grupo
~~~
Thiago Cardoso    - 11796594
Guilherme Pacheco - 11797091
Ciro Falsarella   - 11795593
Pedro Martelleto  - 11795641
~~~
 
# - Circuito
### Diagrama no Falstad
![image1](https://github.com/copach/fonte020/blob/master/CircFalstad.JPG)
 
#### [Circuito no Falstad](http://tinyurl.com/ybstvx5o)
 
#### [Apresentação no Youtube](http://www.youtube.com/watch?v=NRp7nlJM8PE)

&nbsp;
 
### Diagramas no Eagle
 
Esquema do circuito no eagle, com os respectivos componetes e ligações.
![image2](https://github.com/copach/fonte020/blob/master/EAGLE2.jpeg)
 
 
&nbsp;
 
Disposição dos itens na placa PCB, facilitando a aplicação real.
 
![image3](https://github.com/copach/fonte020/blob/master/EAGLE.jpeg)
 
### Função de Cada Componente
- Transformador: é responsável por reduzir a tensão alternada de entrada (cujo pico vale 127V) para uma tensão próxima a 18V.
- Ponte Retificadora: transforma a tensão alternada em tensão próxima a contínua e positiva. Já os diodos que a compõe, servem para direcionar a corrente.
- Resistores: são responsáveis por limitar a corrente elétrica do circuito através do efeito joule.
- Potenciômetro: tem a mesma função de um resistor, a única diferença é que possui resistência váriavel.
- Diodo Zener: como só pode trabalhar em uma única tensão, ficou responsável por manter o potencial em 13V onde foi usado. 
- Transistor NPN: foi conectado no potenciômetro para que consigamos variar a resistência dele, de modo a controlar a corrente que passa na fonte.

 
# - Preços e Especificações
| Componente             | Especificações | Preço |
|:------------------------:|:----------------:|:-------:|
| Diodo Retificador (x4) | 400V e 3A      |[R$1,44](https://www.baudaeletronica.com.br/diodo-1n5404.html)|
| Capacitor              | 330uF e 25V    |[R$0,19](https://www.baudaeletronica.com.br/capacitor-eletrolitico-330uf-25v.html)|
| Diodo Zener            | 13V e 1W       |[R$0,20](https://www.baudaeletronica.com.br/diodo-zener-1n4743-13v-1w.html)|  
| Resistor          (x3) | 1KΩ e 1/4W     |[R$0,24](https://www.baudaeletronica.com.br/resistor-1k-5-1-4w.html)|
| Resistor          (x2) | 200Ω e 1/4W    |[R$0,16](https://www.baudaeletronica.com.br/resistor-200r-5-1-4w.html)|
| Resistor               | 300Ω e 1/4W    |[R$0,08](https://www.baudaeletronica.com.br/resistor-300r-5-1-4w.html)|
| Potenciômetro          | 5KΩ e 0.2W     |[R$1,09](https://www.baudaeletronica.com.br/potenciometro-linear-de-5k-5000.html)|
| Transistor NPN         | BC337          |[R$0,17](https://www.baudaeletronica.com.br/transistor-npn-bc337.html)|  
| **Total**              | -------------- |R$3,57|
 
# - Agradecimentos
Agradecemos ao professor Eduardo do Valle Simões, por tamanha simplicidade, humildade e empenho em ensinar.
