# Biblioteca - 2
<p>Se	desea	realizar	el	modelo	de	un	sistema	de	gestión	bibliográfica.	Para	ello	se	consideran	los	
siguientes	conceptos:</p>
<ul>
  <li>Hay	 “Bases_de_datos”	 que	 tienen	 un	 atributo	 que	 es	 su	 “url”,	 y	 un	 método	
“anadir_publicación”	 (que	devuelve	un	puntero	a	“Publicación”	y	 tiene	un parámetro	que	es	
    un	string).</li>
<li>	Las	bases	de	datos	se	componen	de	“Publicaciones”.</li>
<li>Una	 publicación	 tiene	 dos	 atributos:	 “nombre”	 (de	 tipo	 string)	 y	 “fecha”	 (de	 tipo	 Date	 –
suponerla	ya	implementada).</li>
<li>Hay	varios	tipos	de	publicaciones:	“Articulo_de_conferencia”,	“Capitulo_de_libro”	y	“Libro”.	
A	su	vez	hay	un	tipo	de	libro	que	son	los	“Proceedings”,	que	son libros	compuestos	por	varios	
artículos	 de	 una	 misma	 conferencia.	 Los artículos	 de conferencia	 tienen	 un	 atributo:	
“num_paginas”	(int).	Los capítulos	de	libro	tienen	un	atributo:	“num_capitulo”	(int).	Los	libros	
tienen un	 atributos:	 “ISBN”	 (array	 de	 4	 enteros).	 Los	 proceedings	 tienen	 un atributo:	
“lugar_conferencia”	(string).</li>
<li>	Los	libros	pueden	contener	capítulos	de	libro.</li>
<li>	Los	proceedings	están	compuestos	por	artículos	de	conferencia.</li>
<li>También	 hay	 “Autores”,	 que	 tienen	 tres	atributos:	 “nombre”	 (string),	 “correo_electronico”	
(string)	 y	 “entidad”	 (string),	 y	 un	 método: “añadir_entidad” (no	 devuelve	 nada,	 y	 tiene	 un	
parámetro	de	tipo	string).</li>
<li>Los	autores	pueden	escribir	artículos	y	consultar	bases	de	datos.</li>
</ul>

<p>Utilizando	 herencia	 siempre	 que	 se	 pueda,	 realizar	 un	 diseño	 UML	 de	 clases	 del	 sistema	
indicando:</p>
<ul>
<li>Las	clases	que	se	consideren	necesarias	con	sus	atributos	y	métodos.</li>	
<li>El	tipo	de	privacidad	más	idóneo.</li> 
<li>Las	 relaciones	 entre	 clases:	 asociación,	 dependencia,	 herencia,	 agregación,
composición,	etc. </li>
<li>La multiplicidad	en	 las	 relaciones	entre	 clases.	 Al	menos	 una	 de	 las	 clases	
debe ser	abstracta	(indicarlo	claramente).</li>
