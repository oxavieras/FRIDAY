### A analogia da máquina de suco

Imagina uma máquina de suco. Você coloca frutas nela e ela te devolve suco. Agora pensa em três perguntas:

**Que frutas eu _posso_ colocar?** Só as que a máquina aceita — laranja, limão, maçã. Se você tentar colocar uma pedra, não rola. Esse conjunto de entradas permitidas é o **domínio**.

**Que tipos de líquido ela _teoricamente_ poderia produzir?** Digamos que a máquina foi projetada pra produzir qualquer líquido — água, suco, chá. Esse conjunto de saídas possíveis é o **contradomínio**.

**Que líquido ela _de fato_ produziu?** Com as frutas que você colocou, ela só produziu suco de laranja, limão e maçã — não produziu água nem chá. Esse conjunto de saídas reais é a **imagem**.

A sacada central é essa: o contradomínio é o que a função _poderia_ devolver em teoria, e a imagem é o que ela _realmente_ devolve com os valores do domínio. A imagem sempre está dentro do contradomínio, mas raramente são iguais.
### Traduzindo pra matemática

Vamos pegar uma função concreta: **f(x) = x²**, onde o domínio são os números reais (todos eles, positivos, negativos e zero).

O **domínio** aqui é ℝ — você pode colocar qualquer número real. Nada impede.

O **contradomínio** é também ℝ — a função _poderia_, em teoria, devolver qualquer número real. Ninguém restringiu as saídas no enunciado.

Mas a **imagem** é [0, +∞) — ou seja, só os números maiores ou iguais a zero. Por quê? Porque qualquer número ao quadrado nunca é negativo! Coloca -5: sai 25. Coloca 3: sai 9. Nunca vai sair -4, por exemplo, mesmo que -4 esteja no contradomínio.

Então: a imagem é o subconjunto do contradomínio que a função _realmente alcança_.