# Gestión de Trenes
<p>Se	ha	de	modelar	parte	de	la	funcionalidad	requerida	para	un	subsistema	de	gestión	de	trenes	
de	compañías	ferroviarias.	Los	requisitos	de	almacenamiento	de información	que	se	necesitan	
están	definidos	(con	lenguaje	natural)	como	sigue.</p>
<p>En	primer	lugar,	toda	compañía	 (con	su	denominación)	a	considerar	posee	al	menos	un	tren.	
Cada	 tren	 está	 compuesto	 por	 una	 máquina	 tractora	 y	 al	 menos	 un vagón.	 Pueden	 existir	
vagones	y	máquinas	no	asignados	a	tren	alguno.	Cada	tren tiene	un	código	identificador	propio	
de	 su	 compañía,	 los	 vagones	 una	 capacidad máxima,	 y	 las	 máquinas	 tractoras	 una	 potencia	
máxima.</p>
<p>Una	compañía	tiene	al	menos	un	empleado,	del	que	se	almacenan	sus	principales	datos,	como	
son	el	nombre,	el	número	de	la	seguridad	social	y	el	domicilio.	Según su	trabajo,	estos	pueden	
ser	jefes	 u	 operarios.	 Si	es	jefe,	 se	almacena	 su	 número de	 teléfono.	 Cada	empleado	 puede	
tener	 designados	 un	 conjunto	 de	 máquinas tractoras	 y/o	 vagones.	 A	 su	 vez,	 cada	 máquina	
tractora	 o	 vagón	 podrá	 estar asignado	 a	 un	 conjunto	 de	 empleados.	 Eso	 sí,	 cada	 tren	 tiene	
siempre	asignado su	jefe,	y	cada	máquina	tiene	un	operario	que	la	conduce.</p>
<p>Realizar	 en	 UML	 el	 diagrama	 de	 clases	 que	 recoge	 la	 relación	 existente	 entre	 trenes,	
empleados,	 teniendo	 en	 cuanta	 que	 todos	 los	 atributos	 son	 privados.	 Las clases	 deben	
contemplar	el	acceso	 (get)	y	el	cambio	 (set)	para	 todos	los	atributos menos	en	el	caso	de	la	
potencia	de	la	máquina.	Especificar	relaciones	y multiplicidades.</p>
