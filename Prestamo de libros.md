<h2>Prestamo de libros</h2>

Considerar el Modelo de Dominio presentado en el siguiente diagrama

<img width="733" alt="56707934-49092b80-66f1-11e9-935f-704c81355dc8" src="https://user-images.githubusercontent.com/33643442/111085652-06c08180-84f7-11eb-8298-d87b306a060b.png">


Realizar los Diagramas de Secuencia del Sistema para los siguientes casos de uso:

Prestar de un libro

“Dado el identificador de una persona, el de un libro, y una fecha de devolución, registra el préstamo de ese libro a esa persona.”

Devolver un libro

“Dado el identificador de una persona y el de un libro, registra la devolución del libro que tenía esa persona. En caso de haber expirado la fecha de devolución se incrementa su deuda en 10 veces la cantidad de días que se demoró en devolver el libro.”

Pagar una deuda

“Dado el identificador de una persona y un monto, registra el pago (parcial o total) de la deuda que tenía esa persona.”
