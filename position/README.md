# Entendendo sobre position no CSS
Position: propriedade CSS que define como um elemento qualquer pode ser posicionado no documento da página.

- A propriedade position vem acompanhada de outras 4 propriedades: TOP, BOTTOM, RIGHT e LEFT (topo, abaixo, direita, esquerda)
- Elas vão determinar a localização final do objeto, deslocando o elemento conforme especificado, ex: `position-top: 25px` significa que esse elemento vai se deslocar a 25px do topo.
- Além das propriedades há 5 tipos de positions: STATIC, FIXED, STICKY, RELATIVE e ABSOLUTE
- Por debaixo dos panos todos os elementos já vem na posição static por padrão, significando que ele segue o fluxo da página.
- O position fixed vai fazer o elemento ficar fixo na página idependente do scroll, porque ele é posicionado em relação a viewport que é a página.
- O position sticky fixa na tela quando você chegar na posição de rolagem, ou seja, conforme eu gero o scroll ele se mexe e fica fixo quando chega no topo.
- O position relative está posicionado em sua relação normal, ou seja, as 4 propriedades TOP, BOTTOM, RIGHT e LEFT vão fazer com que o elemento seja ajustado para fora da sua posição normal sem afetar nenhum elemento.
- O position absolute está posicionado em sua relação ao elemento mais próximo dele que possui um position relative e precisa estar em uma hierarquia de divs e caso nao exista um relative ele sera absoluto a pagina.

![position-top](/assets/position-top.png)
![position-static](/assets/position-static.png)
![position-fixed](/assets/position-fixed.png)
![position-absolute](/assets/position-absolute.png)
