# RayCasting

Projeto do IME para criar imagem de esferas utilizando Ray Cast e modelo de reflexição de Phong

## Alunos: 
Leonardo Gomes
Felipe Reyel

3 Imagens foram produzidar com a posição da camera fixa e uma luz branca. Mudança apenas da posição do foco de luz e das componentes ambiente, difusa e especular dos objetos.

## Ball_1: Imagem Verde Lambertiana
Light:
position: (5, 5, 5);

object:
ambient: (0, 0.1, 0)
diffuse: (0, 0.7, 0)
specular: (0, 0, 0)

## Ball_2: Vermelha, Especular
Light:
position: (-3, 0, 5);

object: (red ks=0.8)
ambient: (0.1, 0, 0)
diffuse: (0.7, 0, 0)
specular: (0.8, 0.8, 0.8)

## Ball_3: Magenta, Fundo cinza
Light:
position: (5, 5, 5);

object: (Magenta ks=1)
ambient: (0.1, 0, 0.1)
diffuse: (0.7, 0, 0.7)
specular: (1, 1, 1)
