---
layout: post
title:  Aula
date:   2020-11-19 11:19:55 +0300
image:  aula.png
tags:   [Projeto 2]
---
**Conteúdo**
* TOC
{:toc}

# Contextualização histórica

Nos tempos passados, em todas civilizações, a obervação do céu pode ter sido a atividade mais importante e elegante feita pela humanidade.
O Sol era quase (em algumas civilizações efetivamente) considerado um Deus, a Lua (que possui o "mesmo" tamanho do Sol) auxiliava na criação de lendas e crenças.
As primeiras elucidações científicas buscavam a compreensão dos movimentos dos astros, as razões de existências das estrelas, o fato de serem fixas ou móveis (lembrando que estamos contextualizando conforme os povos primitivos pensavam) levaram a perguntas que todos povos tentaram responder.

Os fênomenos observados, dias, noites, fases da lua, constelações se repetia com certa regularidade. Quando esta regularidade foi conceituada por alguns cientistas e entusiastas da época, o quesito organização possível dos astros começou a se solidificar.
e deveria existir alguns critérios que poderiam ser atribuitos científicamente para explicar estes fatos.

Obviamente o conceito inicial foi que tudo girava em torno da terra, o mais difícil era explicar os movimentos dos planetas em trajetórias circulares.
O primeiro sistema planetário capaz de explicar estes movimentos celestes foi o Sistema Geocêntrico, proposto por Ptolomeu no início da era cristã.
A teoria proposta a Terra ocupava o centro do universo, e tudo girava em torno dela, onde as órbitas do Sol e da Lua eram circulares, e os planetas tinham um conceito mais elaborado.
Os planetas descreviam pequenos ciclos chamados de epiciclos, que também giravam ao redor da terra.
E no fundo de tudo estavam as estrelas que eram supostamente fixas, o objetivo de Ptolomeu e o sistema geocêntrico baseava-se em explicar a variação da velocidade e do sentido destes movimentos.

Já no século XVI, o astrônomo Copérnico prôpos um novo sistema de organização do universo, o Sistema Héliocêntrico, no qual o Sol ocupava o centro do universo, onde esta idéia já havia sido proposta na grécia por Aristarco de Samos, porém rejeitada pelos locais.
Neste sistema a Terra era apenas mais um planeta que girava em torno do Sol e por conseguinte em torno dela mesma, ao redor da Terra girava a Lua, e ao redor de desta grande corrente circular de planetas estava uma esfera fixa onde estavam incrustadas as Estrelas.

## Atividade:

Pense, antigamente no momento do sistema de copérnico a Terra ocupava o centro do universo, logo os navegadores se orientavam pelas estrelas! Considerando nossa tecnologia e sabermos de maneira inerte hoje como é realmente nosso universo, como se justificaria a assertividade destas navegações utilizando-se das estrelas neste meio de navegação.


# Leis de Keppler

Baseado nas observações feitas por Tycho Brahe, o astronômo Kepler formulou 3 leis de movimentos planetários, foram elas:
{% highlight html %}
I) As órbitas dos planetas são elípticas e o Sol se localiza em um dos seus focos.
{% endhighlight %}

{% highlight html %}
II) O segmento de reta traçado do Sol a qualquer planeta (raio vetor) descreve áreas iguais em tempos iguais.
{% endhighlight %}
![]({{site.baseurl}}/img/Kepler-second-law.svg)

Fonte: [Wikipédia](https://pt.wikipedia.org/wiki/Leis_de_Kepler#Terceira_lei_de_Kepler:_lei_dos_per%C3%ADodos) 
{% highlight html %}
III) O quadrado do período de revolução (T²) de cada planeta em torno do Sol é diretamente proporcional ao cubo da distância média (r³) desse planeta ao Sol.
{% endhighlight %}
Matemáticamente falando será:

$$ T²=k.r³ $$

Esta última, confirmaria a teoria de Copérnico, em órbitas elípticas com excentricidade muito mais perto de 0 do que de 1, logo praticamente circulares.

## Atividade:

Pense, considerando o Sol num dos focos de uma elipse, (construa este desenho) e um planeta com a órbita nesta elipse, de maneira totalmente intuitiva e já conhecendo de conteúdos prévios relação de velocidade em relação a tempo e distância, em que ponto teria-se a velocidade máxima deste planeta e que ponto a mínima.


# Lei da gravitação universal


As leis de Kepler descrevem de maneira precisa os movimentos, porém não oferecem resposta ao causa destes movimentos matemáticamente.
Isto coube a Isaac Newton a base teórica que fornceu-nos a resposta matemática:

```sh
	Duas partículas quaisquer se atraem com forças cuja intensidade é diretamente proporcional ao produto de suas massas e inversamente proporcional a distância entre elas.
```

$$ F=G{\frac{m_1 m_2}{r^2}} $$

onde G é a constante gravitacional cujo valor determinado experimentalmente por Cavendish é:

$$ G=6.674 X 10^-{11}{\frac{\textbf{N}\cdotp\textbf{m}^2}{\textbf{kg}^2}} $$

Abaixo temos uma exemplificação da amplitude de aplicação desta importante lei:

![]({{site.baseurl}}/img/NewtonsLawOfUniversalGravitation.svg)

Fonte: [Wikipédia](https://pt.wikipedia.org/wiki/Lei_da_gravita%C3%A7%C3%A3o_universal)

## Atividade:

Pense, se a lei da atração universal vale para tudo no universo, como dois objetos pequenos com o lápis e a borracha não se atraem em cima da mesa.


# Avaliação

1) Considerando o raio da órbita da Terra e de Júpiter, qual o período de revolução de Júpiter em anos terrestres?

$ R(Terra)=1.5 X 10^{11}{m} $

$ R(Júpiter)=7.8 X 10^{11}{m} $


2) Calcule a força de atração gravitacional entre dois corpos de massa 1 Kg distantes a 1 m um do outro.

Explique o resultado se a atração é forte, fraca e o por quê desta.


3) Calcule a intensidade da atração gravitacional entre a Terra e a Lua, considerando as massas informadas abaixo e as distâncias(medidas dos seus respectivos centros).

$ M(Terra)=6.0 X 10^{24}{Kg} $

$ M(Lua)=7.4 X 10^{22}{Kg} $

$ R(Terra-Lua)=3.8 X 10^{8} $

