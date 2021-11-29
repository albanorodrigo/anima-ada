<h2>Ejercicio de Requerimientos</h2>
<p>Se le encarga desarrollar un producto de software para preparar entregas a clientes.
En una Base de Datos de un servidor conectado a una red están registrados los Pedidos de los Clientes y se
dispone también de la información de los artículos que hay en existencia.</p>

<p>Un proceso por lotes debe identificar diariamente de forma automática todos los Pedidos para los que hay
disponibilidad como para cumplir las entregas, con el criterio de atender primero los Pedidos de mayor prioridad.</p>

<p>La prioridad está determinada por una escala de 5 valores. A igual valor de prioridad se atienden primero los
Pedidos más antiguos. El proceso emite un listado con los Pedidos en condiciones de cumplirse total o
parcialmente, con los datos:</p>

<p>nro. Pedido, Fecha Pedido, Hora Pedido, Id. Cliente, Nombre Cliente, Dirección Cliente, Fecha del Día, Hora
(Id.Producto, Descripción Producto, Cantidad Pedido, Cantidad ya Entregada, Cantidad a Entregar, Ubicación)
y un listado adicional con los Pedidos que tienen más de 24 horas y que no pueden cumplirse. El operario
puede cambiar las prioridades de los Pedidos.</p>

<p>El encargado de preparar los envíos va tildando las líneas ya apartadas. Excepcionalmente sucede que no hay
existencia física como para cumplir un envío debido a una discrepancia entre la existencia registrada en el
sistema con la real. En ese caso el encargado anota en el listado la cantidad efectivamente apartada.</p>
<p>El operador puede revisar por pantalla los pedidos que tenía para cumplir y marcarlos como entregados.
Si la cantidad apartada no coincidiera con la Cantidad a Entregar del listado, el operario puede corregir la
Cantidad a Entregar. Al marcar un Pedido como entregado, el producto pasa un mensaje al sistema de control
de existencia para que la actualice, y emite una factura con los datos:</p>
<p>Nro. Factura, Fecha de Factura, Id. Cliente, Nombre Cliente, Dirección Cliente, RUC Cliente
(Id. Producto, Descripción Producto, Cantidad Factura, Precio Unitario, Importe) SubTotal, Importe IVA, Importe
Factura,y deja registrados esos mismos datos en la Base para poder controlar a posteriori el pago y alimentar la
contabilidad.</p>

<br>
<p>1. De acuerdo al enunciado anterior, revise los requerimientos para determinar si hay algun problema, por ejemple consistencia, ambiguedad, conflictos. ¿
Contiene alguna decisión de diseño o de implementación?</p>
<p>A. Describa los requerimientos para este problema</p>
<p>B. Piense para este problema, requerimientos no funcionales de tipo:
<ol>
<li>Del producto</li>
<li>De la organización</li>
<li>Externos</li>
</ol>
</p>

<p>2. A veces un cliente plantea un requerimiento que uested sabe es imposible de implementar. ¿Qué deberia hacer, incluir el requerimiento en los documentos de definición y especificación pensando
en más adelante encontrar alguna forma de cumplirlo o pensando en pedir más adelante que sea dejado de lado? Discuta las implicancias éticas de prometer lo que sabe no puede brindar.</p>
<p>3. A veces parte de un sistema se puede construir rápidamente para mostrar la factibilidad o la funcionalidad al cliente. Normalmente ese prototipo es incompleto. El sistema real se construye después que el cliente y el desarrollador
evalúan el prototipo. ¿Cuando debiera escribirse el documento de requerimientos del sistema, antes o después de desarrollar el prototipo? ¿Por qué?</p>
<p>4. ¿Qué tipo de problemas se deben buscar al hacer una revisión de los requerimientos? Construya una lista de verificación para esos problemas. ¿Es posible tener una lista universal o es mejor disponer de una lista específica para el area de aplicación?<p/>

<p>5. De acuerdo al enunciado anterior:
<ol>
<li>Identifique actores y casos de uso.</li>
<li>Describa cada uno de los casos de uso.</li>
<li>Construya un DFS (Diagrama de flujo de datos) que represente el flujo de información en ese sistema incluyendo los tratamientos manuales de información</li>
<li>Compare las descripciones de 2 y 3 y evalúe las virtudes y limitaciones de cada una.</li>
</ol>
</p>
</p>
