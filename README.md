![imagem local](/imagens_readme/logo.jpg)



# HTML CSS JAVASCRIPT

  - [Tecnologias Usadas](#Tecnologias-Usadas)
  - [Sobre](#Sobre)
  - [Aula 1 Tags](#Aula-1-Tags)
  - [Aula 2 Estrutura Básica HTML](#Aula-2-Estrutura-Básica)
  - [ Aula 3 Introdução ao CSS](#Aula-3-Introdução-ao-CSS)
  
  
## Tecnologias Usadas

[HTML5](https://pt.wikipedia.org/wiki/HTML5) /  [CSS3](https://pt.wikipedia.org/wiki/CSS3) / [JavaScript](https://pt.wikipedia.org/wiki/JavaScript)


## Sobre


Aprendendo Front-end com HTML5, CSS e JavaScript do zero ao avançado com aprendizados retirados de um canal [aulas no youtube](https://www.youtube.com/watch?v=0Pm6ex5HDGY&list=PL1dUY2RYa2RhNhm-QTuNIifVpc59wrpFP&index=1&ab_channel=Serliv) 


## Aula 1 Tags



![imagem local](imagens_readme/Aula_1/escrevendo_html_no_VSCode.png)


As tags são elementos que definem a estrutura e o conteúdo de uma página web. Elas são usadas para marcar partes específicas do conteúdo — como parágrafos, títulos, imagens, links, listas, tabelas etc. Para
Definir uma tag você precisa abrir e fechar um elemento (dessa forma "<h1></h2>"), sendo o segundo elementro o fechamento deve conter "/". 


O "h1" é o elemento do titulo, que usamos para descrever um titulo. Existe também o h2 h3 h4... que são substitulos que responde uma hierarquia.


O proximo elemento é <p> que é usado para determinar um paragrafó com texto, e você pode utilizar outras tags dentro, respeitando a hierarquia.

A tag "a" serve para você adicionar referencia para link, você pode refenciar para uma pagina que está no seu projeto com o "<a href= "outrapagina.html >", você referenciar para alguma outra pagina web com
"<a href= "http://www.google.com>", entre outras formas de link.

Existe tags que não repcisa de fechamento é o caso da <hr>, ela serve para quebrar linha.

A tag "ur" serve para criar uma lista não ordenada em conjunto com a tag "li" que serve para listar os itens .

A tag "ol" serve para criar uma lista não ordenada em conjunto com a tag li" que serve para listar os itens .

As tags "strong" e "b" servem para dizer que tal palavra ou frase está em negrito

As tags "em" e "i" servem para dizer que tal palavra ou frase está em itálico.

Na Aula o professor propos aos alunos fizessem um exercicio para ratificar o aprendizado:


![imagem local](imagens_readme/Aula_1/exercio_proposto_sobre_tag.png)


A Aula é personalizado então você pode fazer do jeito que quiser.


## Aula 2 Estrutura Básica


A estrutura básica de HTML é o esqueleto de qualquer página web. Ela define como o conteúdo da página será organizado e interpretado pelo navegador:


![imagem local](imagens_readme/Aula_2/estrutura_base_html.png)



Para começar a explicação da estrutura iremos falar sobre "!DOCTYPE html". Ele deve ser o primeiro elemento da página e o objetivo dele é indicar ao navegador que o documento está usando HTML5. Seguindo para "html lang=pt-BR", ele é o elemento raiz da página, com o atributo lang indicando o idioma. O Head Contém metadados, como título, codificação de caracteres, estilos, scripts etc, "meta charset=UTF-8": Define o conjunto de caracteres, no caso o UTF-8 permite acentos e símbolos, seguindo para title Define o título que aparece na aba do navegador, entre outros. O body, onde vai o conteúdo visível da página, como textos, imagens, links, etc.


Importante comentar que essa estrutura suas tags tem um valor semantico e não tem impacto visual, o retorno da pagina seria esse:


![imagem local](imagens_readme/Aula_2/estrutura_base_html_retorno.png)


## Aula 3 Introdução ao CSS


O CSS3  é a linguagem usada para estilizar páginas HTML,  ou seja, para deixar bonito . Ele permite mudar cores, fontes, tamanhos, posicionamentos, e até criar animações. Existe três formas de usar o CSS, inline que é dentro da própria tag do html, interno que seria dentro do heard dentro do corpo do style e o externo que seria um arquivo com o formato css. 



![imagem local](/imagens_readme/Aula_3/codigo_css.png)



Nesse exemplo eu usei o CSS interno no heard. A estrutura básica é a propriedade html{ propriedade css : o tipo }. 

O retorno para esse arquivo html e css:


![imagem local](/imagens_readme/Aula_3/resultado.png)

