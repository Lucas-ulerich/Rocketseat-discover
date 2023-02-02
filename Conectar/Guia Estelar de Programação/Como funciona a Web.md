# Como funciona a WEB?

Quando entramos em um site através de um navegador, qual caminho usamos?

+ Digitamos o site no google
+ Clicamos no site que escolhemos
+ Pronto :)

Esse é o caminho fácil, a fazemos isso todos os dias, mais não sabemos o que acontece por debaixo dos panos. Ai que vem o caminho avançado e é esse que temos que entender!

1. Digitamos o nome do site que queremos *rocketseat* por exemplo

	O Navegador converte o nome do site que escrevemos em uma **URL**
	Rocketseat vira https://rocketseat.com.br
	Nessa **URL** temos o **HTTPS** que é um protocolo de segurança, ele significa **H**ypertext **T**rasnfer **P**rotocol, a função dele é trocar mensagem entre outros computadores. esse mensagem que é enviada para outros computadores é quebrada em diversos pedaços (Chunks)

	E temos a **URL** que significa **U**niform **R**esource **L**ocator, ele é um localizador e identificador de um recurso, o recurso em questão é o site que digitamos no **Google**

2. Agora inicia uma linha de comunicação através do protocolo **TCP** entre o computador **cliente** até o computador que tem a página **servidor**.

	+ **Cliente**: É o computador, dispositivo ou aplicativo que fez o pedido. Nesse casso o navegador.
	+ **Servidor**: É o computador que recebeu o pedido e te envio o site.
	+ **TCP:** **T**ransmission **C**ontrol **P**rotocol, a sua função é garantir que todos os pacots cheguem corretamente ao destino.

3. A nossa **URL** é convertida em um endereço de IP através do DNS
	+ **IP:** Significa **I**nternet **P**rotocol a sua função é o endereçamento dos computadores, cada computador tem um IP único.
	+ **DNS:** **D**omain **N**ame **Servers** a sua função é converter um domínio (URL) em um endereço **IP.**

4. Agora nosso pedido está percorrendo por diversos proxies:
	+ Proxy é qualquer dispositivo no meio do caminho
	+ Modem, Roteador, outros computadores.
	+ A função dele é o encaminhamento dos pacotes (chunks)

5. O pedido chega ao servidor

6. O servidor analisa o pedido e te dá uma resposta, neste caso positiva

7. O caminho de volta é semelhante ao caminho de ida, passando pela linha de comunicação que foi criada.

8. O navegador recebe os pedaços e monta a tela do site para você.

9. Esse processo acontece muitas vezes, pois para cada recurso (HTML, CSS, JavaScript, Imagem...) é feita uma nova conexão.

Esse é o caminho avançado, isso tudo acontece em questão de segundos o que mostra que a internet é simplesmente incrível! 