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
![image1](https://i.imgur.com/Lb4f5qB.png)
 
### [Circuito no Falstad](http://tinyurl.com/y8y5ud8v)
 
### [Apresentação no Youtube](http://www.youtube.com/watch?v=NRp7nlJM8PE)
 
### Diagramas no Eagle
 
Esquema do circuito no eagle, com os respectivos componetes e ligações.
![image3](https://i.imgur.com/UUYewQK.jpg)
 
 
&nbsp;
 
Disposição dos itens na placa PCB, facilitando a aplicação real.
 
![image2](https://i.imgur.com/uIXhPkZ.jpg)
 
### Função de Cada Componente
- Transformador: reduzir a tensão da corrente.
- Ponte Retificadora (4 Diodos Retificadores) e Capacitor: transformar a tensão alternada em tensão próxima a contínua.
- Resistores: são responsáveis por limitar a corrente elétrica em um circuito através do efeito joule (conversão energia elétrica em térmica através da colisão entre os elétrons e a camada do resistor).
- Potenciômetro: tem a mesma função de um resistor, a única diferença é que ele possui resistência váriavel.
- Diodo Zener: é responsável pela regulação da tensão no circuito.
- Transistor NPN: controla a intensidade da corrente, permitindo a economia da mesma.
 
# - Preços e Especificações
| Componente             | Especificações | Preço |
|:------------------------:|:----------------:|:-------:|
| Diodo Retificador (x4) | 400V e 3A      |[R$1,44](https://www.baudaeletronica.com.br/diodo-1n5404.html)|
| Capacitor              | 330uF e 25V    |[R$2,00](https://www.baudaeletronica.com.br/capacitor-eletrolitico-330uf-25v.html)|
| Diodo Zener            | 13V e 1W       |[R$0,21](https://www.baudaeletronica.com.br/diodo-zener-1n4743-13v-1w.html)|  
| Resistor               | 220Ω e 1/4W    |[R$0,08](https://www.baudaeletronica.com.br/resistor-220r-5-1-4w.html)|
| Resistor               | 360Ω 1/4W      |[R$0,08](https://www.baudaeletronica.com.br/resistor-360r-5-1-4w.html)|
| Resistor               | 850Ω e 1/4W    |[R$0,08](https://www.baudaeletronica.com.br/resistor-750r-5-1-4w.html)|
| Potenciômetro          | 2000Ω e 0.2W   |[R$1,09](https://www.baudaeletronica.com.br/potenciometro-linear-de-2k-2000.html)|
| Transistor NPN         | BC337          |[R$0,17](https://www.baudaeletronica.com.br/transistor-npn-bc337.html)|  
| **Total**              | -------------- |R$5,15|
 
# - Agradecimentos
Agradecemos ao professor Eduardo do Valle Simões, por tamanha simplicidade, humildade e empenho em ensinar.
