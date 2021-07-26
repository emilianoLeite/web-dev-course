# Module 2
<h1> W3 Schools JavaScript </h1>

- <a href:'https://www.w3schools.com/js/js_datatypes.asp'> Data Types </a>
- <a href:'https://www.w3schools.com/js/js_functions.asp'> Functions </a>
- <a href:'https://www.w3schools.com/js/js_objects.asp'> Objects </a>
- <a href:'https://www.w3schools.com/js/js_arrays.asp'> Arrays </a>
- <a href:'https://www.w3schools.com/js/js_array_methods.asp'> Array Methods </a>

<h1> JustJavaScript </h1>

<h2> Equality of Values (módulo 6) </h2>

 - <p> 3 tipos de igualdade </p>
 - <p> Igualdade estrita (a===b): igualdade mais usada devido a sua confiabilidade </p>
 - <p> Igualdade solta (a==b): igualdade menos usada devido a sua propensao a erros (devido a diversidade de valores convertidos para false ou true) </p>
 - <p> Igualdade de mesmo valor (object.is(a,b)): igualdade que verifica se dois objetos apontam para o mesmo valor, um tipo de igualdade importante ao considerar a complexidade dos objetos (como visto no módulo anterior) </p>
 - <p> Em quase todos os casos, a igualdade estrita se comportará de maneira similar ä igualdade de mesmo valor, sendo as excecoes NaN e -0 </p>
  
  <h2> Properties (módulo 7) </h2>
  
  - <p> Propriedades obrigatoriamente necessitam de um objeto para existirem, já que sao a 'ponte' entre os objetos e seus respectivos valores </p>
  - <p> Propriedades sao parecidas com variaveis </p>
  - <p> Ambas apontam para valores, mas a diferenca é que os fios das variaveis partem do codigo que criamos enquanto os fios das propriedades partem dos objetos que criamos </p>
  - <p> Quando se muda o valor de uma propriedade, a mesma apenas apontará para o novo valor desejado (propriedades nao contém valores!!) </p>
  - <p> Regras de leitura de propriedade: <br> 1- Figure out the value of the part before the dot (.); <br> 2- If that value is null or undefined, throw an error immediately; <br> 3- Check whether a property with that name exists in our object. <br>
a. If it exists, answer with the value this property points to. <br>
b. If it doesn’t exist, answer with the undefined value </p>
   
