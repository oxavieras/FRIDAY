### Distância entre dois pontos

Imagina dois pontos no plano: **A = (x₁, y₁)** e **B = (x₂, y₂)**.

A distância entre eles é calculada assim:

$$d_{AB} = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$$

**Por que essa fórmula?** Olha o raciocínio:

Se você traçar um triângulo retângulo entre os dois pontos, os catetos são a diferença em x e a diferença em y. A distância é a hipotenusa — e aí entra o **Teorema de Pitágoras**. A fórmula é literalmente Pitágoras disfarçado! 🔺

**Exemplo rápido:** A = (1, 2) e B = (4, 6)

$$d= \sqrt{(4-1)^2 + (6-2)^2} = \sqrt{9 + 16} = \sqrt{25} = 5$$
### Ponto Médio

O ponto médio **M** de um segmento AB é o ponto que fica exatamente no meio. As coordenadas dele são a **média** das coordenadas dos extremos:

$M = \left(\frac{x_1 + x_2}{2},\ \frac{y_1 + y_2}{2}\right)$

**Faz sentido?** Você só está tirando a média entre os dois valores de x e entre os dois de y. Simples assim.
### Condição de Alinhamento

Três pontos A, B e C são colineares (estão na mesma reta) quando a área do triângulo formado por eles é **zero**. Essa área é calculada assim:

$$A=1/2⋅∣xA(yB−yC)+xB(yC−yA)+xC(yA−yB)∣$$

Se der zero, estão alinhados. Se der diferente de zero, formam um triângulo.