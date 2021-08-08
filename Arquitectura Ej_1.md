# Arquitectura Ej: 1

<p>
Para cada uno de los problemas descriptos a continuación, modele el estilo arquitectónico
solicitado. Para cada caso analice las ventajas y desventajas del modelo, e indique si podría
utilizar otro estilo arquitectónico (o combinación de estilos). En caso afirmativo, justifique
adecuadamente su decisión y realice además el modelo alternativo. 
</p>
<h5>Tubos y filtros</h5>
<p>Se desea contar con un sistema capaz de mejorar la calidad del sonido de escuchas
telefónicas, grabación a distancia de conversaciones, etc. El sonido será digitalizado y a
partir de allí se lo someterá a diversas transformaciones para mejorar su calidad. Las transformaciones posibles son: </p>

<ul>
<li>Dividir los sonidos según su frecuencia, lo que produce varias bandas de sonido diferentes que pueden ser analizadas separadamente o vueltas a reunir.</li> 
<li>Disminuir la velocidad con que se reproduce el sonido de una cantidad fijada dinámicamente por el usuario. </li>
<li>Eliminar todos los sonidos de una frecuencia dada por el usuario. </li>
<li>Aumentar y disminuir el volumen en una cantidad fijada por el usuario. </li>
</ul> 
<p>El usuario puede determinar en cualquier paso si desea escuchar el resultado. Cada vez que se realiza una mejora a la calidad del sonido, es el usuario quien decide qué operación de las
  disponibles desea realizar.</p>
 
<h5>Sistemas en capas o estratificados</h5>
<p>Los pacientes de una guardia de terapia intensiva son monitoreados por dispositivos electrónicos análogos adosados a sus cuerpos. Los dispositivos miden los signos vitales de los pacientes. Hay un sensor para el ritmo cardíaco (activo, una señal para cada latido del
corazón), presión sanguínea (pasivo) y la temperatura (pasivo). Se necesita un programa que lea los signos vitales con una frecuencia especificada para cada paciente. Los valores leídos
serán comparados con rangos que serán reportadas con mensajes de alarma en el monitor del box de enfermería. También debe mostrarse un mensaje apropiado si falla un dispositivo. Además, se requiere almacenar los datos y proveer reportes estadísticos.
</p>
 
<h5>Sistemas basados en eventos</h5>
<p>
Debido al gran éxito de la película “El código Da Vinci”, mayor cantidad de personas se ha acercado al Museo del Louvre para conocer las obras de Leonardo Da Vinci, en especial, “La
Mona Lisa”. Esta obra ha sido cambiada a una sala más importante para que pueda ser mejor apreciada por el público. Entre las tantas medidas de seguridad tomadas, se instaló
además un importante sistema de iluminación en forma automática de manera tal de mantener la luz dentro de cierto rango que permite a los visitantes apreciar la obra siempre
correctamente iluminada y al mismo tiempo no provocarle daños serios. La sala cuenta con ventanas e iluminación artificial. Cerca de la obra de arte se instaló un sensor que mide la
cantidad de luz que le llega a la obra. El sistema de software de los sensores deberá mantener la cantidad de luz sobre la obra dentro de ciertos límites pre-establecidos. Éstos
son modificados automáticamente de manera tal de regular su intensidad, aumentándola o disminuyéndola de manera discreta según haga falta. El sistema deberá optar primero por
utilizar la luz proveniente de las ventanas, y si esta no es suficiente deberá hacer uso de la iluminación artificial. El sensor no puede “manejar” la luz natural que le llega a la obra
aunque sea demasiada, pero sí puede detectar cuándo le hace falta utilizar la luz artificial en función de los límites ingresados por un especialista en el sistema de software del museo.
</p>
