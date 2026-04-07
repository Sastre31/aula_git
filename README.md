## Padding
- Padding define o espaço ao redor do conteúdo.
### 1. Sintaxe e propriedades individuais
Você pode definir o espaçamento interno para lados específicos usando estas propriedades: 
padding-topEspaço na parte superior.
padding-rightEspaço à direita.
padding-bottomEspaço na parte inferior.
padding-leftEspaço à esquerda. 
W3Schools
W3Schools
 +5
### 2. A propriedade taquigráfica
Essa paddingpropriedade permite alinhar todos os lados em uma única linha: 
MDN Web Docs
MDN Web Docs
 +1
Valores 	Exemplo	Resultado
1 valor	padding: 10px;	Todos os quatro lados têm 10px.
2 valores	padding: 10px 20px;	Superior/Inferior = 10px; Esquerda/Direita = 20px.
3 valores	padding: 10px 20px 30px;	Superior = 10px; Esquerda/Direita = 20px; Inferior = 30px.
4 valores	padding: 10px 5px 15px 20px;	No sentido horário : Superior (10), Direita (5), Inferior (15), Esquerda (20).
### 3. Principais características
Fundos: Ao contrário das margens (que são transparentes), o preenchimento herda a cor ou imagem de fundo do elemento.
Sem valores negativos: os valores de preenchimento devem ser positivos ou zero; valores negativos são inválidos.
Unidades: Você pode usar unidades absolutas como pxou unidades relativas como %, em, ou rem. As porcentagens são calculadas com base na largura do bloco que contém o valor.
Dimensionamento da caixa: Por padrão ( content-box), adicionar preenchimento aumenta a largura/altura total do elemento. Para incluir preenchimento dentro da largura definida, use box-sizing: border-box;

## Margin
- Margin é o que define para criar espaço ao redor de elementos, fora de quaisquer limites definidos.

Propriedades de Margem Individual
Você pode definir a margem de cada lado individualmente: 
margin-topEspaço acima do elemento.
margin-rightEspaço à direita.
margin-bottomEspaço abaixo.
margin-leftEspaço à esquerda. 
MDN Web Docs
MDN Web Docs
 +5

Sintaxe abreviada
A propriedade abreviada de margem pode assumir de um a quatro valores: 
MDN Web Docs
MDN Web Docs
 +1

1 valor: margin: 10px; (Todos os quatro lados têm 10px).
2 valores: margin: 10px 20px; (Superior/inferior: 10px, Esquerda/direita: 20px).
3 valores: margin: 10px 20px 30px; (Superior: 10px, Esquerda/Direita: 20px, Inferior: 30px).
4 valores: margin: 10px 20px 30px 40px; (Superior, Direita, Inferior, Esquerda — sentido horário). 
Maujor
Maujor
 +6

Valores comuns
Comprimento: Pixels ( px), em, rem, etc..
Porcentagem ( %): Relativa à largura do elemento que a contém.
autoO navegador calcula a margem. Definir margin: 0 auto;a largura de um elemento com uma largura fixa é uma maneira comum de centralizá-lo horizontalmente dentro do elemento pai.
Valores negativos: Podem ser usados ​​para aproximar ou sobrepor elementos.

## Border

- Border é o que define #
