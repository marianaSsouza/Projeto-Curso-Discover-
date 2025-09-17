# Projeto Curso Discover
> o propósito deste curso é de nivelamento do HTML, CSS e JavaScript.
> Aqui é o meu formato de revisão para a primeira avaliação de Desenvolvimento de Aplicações Web.

---
## Cascading - Cascata
- Quando há 2 (ou mais) declarações, a última será mais relevante
![prioridade de cor background](./img-notion/cascading-prioridade.png)

## Specificity - Especificidade
- Cada seletor tem um peso e a soma dos pesos
- A soma desses pesos será levada em consideração, assim cada declaração será mais específica.
- Os tipos de especificação são <u>#id</u>, <u>.class</u>, <u>element</u>

![especificidade #id](./img-notion/especificidade-id.png)
![especificidade .class](./img-notion/especificade-class.png)
![especificidade element](./img-notion/especificidade-element.png)

- O efeito cascata **perde prioridade** e será priorizado a especificidade da declaração.

![especificidade arquivo HTML](./img-notion/especificidade-arqv-html.png)
![especificidade arquivo CSS](./img-notion/especificidade-arqv-css.png) 

- Essa será a saída:

![especificidade arquivo HTML](./img-notion/resultado-especificidade.png) 

- caso os pesos sejam iguais (dois paragrafos sem especificação, por exemplo), a ultima alteração é a que conta (cascata)