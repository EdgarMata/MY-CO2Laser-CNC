# Ajustar posição do material

Aqui vamos explorar um passo essencial para garantir o sucesso dos nossos cortes:

O posicionamento do desenho no material. Para isso, é crucial compreender o funcionamento do painel de controle no Carbon Studio. Que tal dar uma olhada a esse artigo da nossa série sobre o [Studio]?

Já se sente confortável em operar a máquina? Então vamos para o próximo passo!

[Studio]: https://gadgetpluskdb.github.io/Carbon-FAQS/studio/primeiros-passos/comando-movimento/

Ajustando o desenho na área de trabalho do Carbon Studio
Independentemente se o desenho foi criado dentro do Carbon Studio ou importado de outro software, é necessário posicioná-lo na posição zero dentro do software.

* Selecione os elementos que deseja cortar. A posição em relação aos eixos X e Y é indicada nas caixas destacadas na Figura 1.

<figure markdown="span">

  ![](../images/posicionamento.png){ width="628" }
  <figcaption>Figura 1 - Desenhos em local aleatório</figcaption>

</figure>

* Ajuste a posição dos desenhos para X=0 e Y=0. Isso moverá os elementos selecionados para a posição zero dentro do software.

<figure markdown="span">

  ![](../images/posicionamento_0x0.png){ width="486" }
  <figcaption>Figura 2 - Desenhos na posição zero</figcaption>

</figure>

O Carbon Studio reconhece o canto superior esquerdo como ponto inicial.

## Definindo o ponto inicial de corte na Carbon

Para que a máquina saiba de onde iniciar o corte, é necessário definir o ponto inicial.

* Movimente o cabeçote do laser com as setas no painel de controle.

<figure markdown="span">

  ![](../images/ferramenta-mov-01.png){ width="443" }
  <figcaption>Figura 3 - Movimentação cabeçote laser setas</figcaption>

</figure>

* Escolha o local onde deseja iniciar o corte. Para otimizar o uso do material, posicione-o no canto superior esquerdo.

<figure markdown="span">

  ![](../images/foto-interior-01.png){ width="800" }
  <figcaption>Figura 4 - Posicionamento do cabeçote no material </figcaption>

</figure>

* Considerando a posição do bico do laser, clique em "definir início" no painel de controle.

<figure markdown="span">

  ![](../images/ferramenta-mov-02.png){ width="265" }
  <figcaption>Figura 5 - Definir início</figcaption>

</figure>

## Criando referências

Ao fazer esses ajustes de posicionamento, estabelecemos uma relação entre a posição do desenho no material e o início do corte: o ponto zero do desenho coincide com o ponto de início do corte!

A máquina considera sempre como ponto inicial a última definição realizada. Portanto, se mover o cabeçote do laser para uma nova posição e iniciar um novo corte, ele retornará ao ponto definido anteriormente! Defina sempre o ponto de início no software (Figura 3).

## Verificando o posicionamento do desenho no material

Para garantir o melhor aproveitamento da área de trabalho, é importante conhecer o espaço que o desenho ocupará no material. Para isso, utilizamos o recurso "Frame".

* Selecione os elementos do desenho que deseja verificar e clique em "preview > frame", conforme indicado na Figura 4.

<figure markdown="span">

  ![](../images/preview-frame.png){ width="583" }
  <figcaption>Figura 6 - Preview > Frame</figcaption>

</figure>

* O recurso de frame facilita a utilização de retalhos de material, pois permite verificar se o desenho caberá no espaço desejado.

<figure markdown="span">

  ![](../images/foto-interior-02.png){ width="800" }
  <figcaption>Figura 7 - Aproveitamento de retalhos</figcaption>

</figure>

## Tamanho do desenho vs. área de trabalho da Carbon.

É crucial lembrar que o tamanho do objeto não pode exceder a área de trabalho da máquina, que é de 600mm de comprimento por 400mm de largura. Caso isso ocorra, seu trabalho não será executado corretamente e/ou o cabeçote do laser começará a bater nas laterais da máquina, emitindo um ruído indicando que está forçar o motor. Portanto, verifique sempre o tamanho do desenho na área de trabalho usando o recurso "frame".

Neste artigo, exploramos como posicionar o desenho no material para otimizar nosso trabalho! Acompanhe-nos no próximo artigo, onde explicaremos como definir a [velocidade e potência] da máquina.

[velocidade e potência]: https://gadgetpluskdb.github.io/Carbon-FAQS/manual/primeiros-trabalhos/velocidade-potencia/
