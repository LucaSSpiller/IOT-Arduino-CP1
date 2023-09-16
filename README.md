<h1>IOT-Arduino-CP1</h1> 
<p><strong>Link do vídeo de explicação:</strong> http://bit.ly/video-explicacao-cp1</p>
<h2>Detalhes do Projeto:</h2>

<p>O pequeno projeto está sendo baseado na variação de temperatura, onde a cada pólo da temperatura é aceso o led correspondente à ela.</p>
<p>Materiais usado: 3 Leds, 1 Sensor de temperatura, 1 Placa Arduíno Uno, 1 Placa de ensaio pequena.</p>
<p>O sensor de temperatura está ligado à três fios, <strong>vermelho</strong>, <strong>preto</strong> e <strong>laranja</strong>. O <strong>vermelho</strong> está sendo ligado em 3.3v, na potência, o <strong>preto</strong> é o terra, está ligado ao GND, e o <strong>laranja</strong> é o fio que emite o sinal ao sensor.</p>
<br>
<br>
<h3><strong>Código de simulação:</strong></h3>

<p>Foi feito um código de simulação para testar o funcionamento.</p>
<p>O pino analógico vai ser lido, e se a temperatura estiver entre 20 e 100 graus, o pino 7 será aceso, que é o azul.</p>
<p>Se estiver entre 101 e 200 graus, o pino 6 será aceso, que é o amarelo.</p>
<p>E acima de 201°, acende o pino 5, que é o vermelho.</p>
<p><strong>Obs:. Para testar, basta clicar em cima do Sensor de temperatura e direcioná-lo para o lado preferir.</strong></p>
<br>
<br>
<h3><strong>Demonstração no Monitor:</strong></h3>
<p>No monitor será mostrado as temperaturas definidas no Sensor, onde a temperatura mínima 20° e á máxima é 358°.</p>
<p>O teste é baseado na temperatura, definindo se ela é ALTA, MÉDIA ou BAIXA.</p>
