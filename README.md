# Projeto Curso Discover
> o propósito deste curso é de nivelamento do HTML, CSS e JavaScript.
> Aqui é o meu formato de revisão para a primeira avaliação de Desenvolvimento de Aplicações Web.

---
## HTML & CSS
### Cascading - Cascata
- Quando há 2 (ou mais) declarações, a última será mais relevante
![prioridade de cor background](./img-notion/cascading-prioridade.png)

#### Specificity - Especificidade
- Cada seletor tem um peso e a soma dos pesos
> A soma desses pesos será levada em consideração, assim cada declaração será mais específica.
> Os tipos de especificação são <u>#id</u>, <u>.class</u>, <u>element</u>

![especificidade #id](./img-notion/especificidade-id.png)
![especificidade .class](./img-notion/especificidade-class.png)
![especificidade element](./img-notion/especificidade-element.png)

- O efeito cascata **perde prioridade** e será priorizado a especificidade da declaração.

![especificidade arquivo HTML](./img-notion/especificidade-arqv-html.png)
![especificidade arquivo CSS](./img-notion/especificidade-arqv-css.png) 

- Essa será a saída:

![especificidade arquivo HTML](./img-notion/resultado-especificidade.png) 

- caso os pesos sejam iguais (dois paragrafos sem especificação, por exemplo), a ultima alteração é a que conta (cascata)

### Box Model 
- Tudo são caixas!
> Todos os elementos HTML serão considerados uma caixa

- Caixas possuem determinadas propriedades
> essas propriedades são o seu **conteúdo, largura, altura, borda, preenchimento (espaço interno), espaçamento (espaço externo)**. 

![boxModel arquivo HTML](./img-notion/boxModel-arqv-html.png) 
![boxModel arquivo CSS](./img-notion/boxModel-arqv-css.png) 

- Ele aparece assim na web

![boxModel resultado web](./img-notion/resultado-boxModel.png) 


---
## JavaScript
### O que é?
- Linguagem de programação
> interpretada e executada pelos navegadores

- Inteligência da tríade 
> HTML é a estrutura, CSS é a beleza e JS é a inteligência 

- Não é **JAVA** 
> Apesar do nome ser semelhante, são linguagens diferentes

### Por que será usado JS?
- Aplicativos
> para WEB, Desktop (Electron) e Mobile (React Native)

- Empresas Famosas 
> Instagram, Google, Netflix, Tiktok... entre outras

- Moderna e Viva 
> Comunidade e linguagem que cresce cada vez mais 

### Instruções e sintaxe em JS
- Toda linguagem é escrita com esses 2 princípios

1. Instruções (declarações)
-> ordens ao computador

2. Sintaxe 
-> maneira correta de escrever 

![boxModel resultado web](./img-notion/alerta-js.png) 

💬**Existem *palavras reservadas da linguagem*. Elas são responsáveis em dar significado a diversas instruções!!**

### Executando JavaScript 
**Podemos executar diretmente no Navegador**
- Ferramenta ***DevTools***
> apertando o atalho *F12* no seu teclado 

- Plataformas online 
> fronteditor.dev e codepen.io

- Projeto Local 
> arquivos no computador 

### Variáiveis 
- É uma caixinha onde guardamos um *tipo de dados* para usar mais tarde

### Tipos de dados
- Informações que podem ser em *textos, números, booleanos* (valores lógicos: verdadeiro ou falso) ou dados mais *estruturados* 





