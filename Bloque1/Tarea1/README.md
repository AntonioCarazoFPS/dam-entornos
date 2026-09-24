# Tarea1T1
--------------------------------------------------------------------------------------------
Creacion de una aplicacion.
--------------------------------------------------------------------------------------------
Primero pensariamos la idea de nuestro app, en este caso vamos a hacer una aplicacion la cual te calcule tu IMC y apartir de el, te haga un calculo de calorias diarias y te aporte una rutina para llegar a la meta diaria. La meta dependera de lo que elijas, si decides que quieres perder peso la rutina y la alimentacion se adaptara a la perdida de peso, en cambio si decide ganancia muscular se aportaria la informacion necesaria.
En la interfaz principal disponemos de una interfaz intuitiva en la que te pide: tu altura, tu peso, tu edad y tu sexo. Con esos datos hace el calculo de IMC y accedemos a la siguiente interfaz.
En la siguiente interfaz elegimos que queremos si queremos ganancia muscular o perdida de peso, en la cual tendremos que clickar en un boton con nuestra eleccion, tras esto saltaremos a la siguiente interfaz.
En la tercera interfaz nos indica una rutina de deporte segun nuestro estado, y la cantidad de calorias diarias, aceptamos y ya tendriamos desbloqueada la ultima interfaz.
En la ultima interfaz se añadiria una tabla con los 7 dias de la semana, en la cual aparece los siguientes apartados, peso, ejercicio fisico en ese dia, kcal, proteinas, hidratos de carbono y grasa consumidas a lo largo del dia y si hemos completado la meta de hoy. Todo esto se ira rellenando a lo largo del dia 
--------------------------------------------------------------------------------------------
La plataforma pensada seria dispositivos moviles(Android/IOS).
--------------------------------------------------------------------------------------------
El lenguaje elegido seria Java y SQL
--------------------------------------------------------------------------------------------
Ejemplo:
Double peso = Double.parseDouble(System.console().readLine("Escribe tu peso: "));
Double altura = Double.parseDouble(System.console().readLine("Escribe tu altura"));
Double IMC = peso / (altura * altura);
--------------------------------------------------------------------------------------------
En un principio todo esto residiria en un archivo java.

