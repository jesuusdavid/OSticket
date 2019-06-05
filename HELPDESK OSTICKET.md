##OSTICKET##
</br>
###Preparación para instalar###
</br>
-Necesitas descargarte el [OSTICKET](https://osticket.com/download/) desde su web de descargas.
-Descargamos [Xampp](https://www.apachefriends.org/es/download.html) desde su web oficial.
</br>
*empezaremos instalando Xampp*
![](images/3.png)
</br>
*Despues vamos a la ruta de htdocs de xampp, y extraemos la carpeta de OSTICKET\(que antes nos hemos descargado\)en htdocs*
![](images/4.png)
</br>

###configuración preinstalación###

*iremos a la ruta "localhost/osticket/upload" y nos saldra esta pantalla, le dariamos a continue:*
![](images/5.png)
</br>
*Después nos sale un error que se soluciona cambiando el nombre de dos archivos, nos sale este error:*
![](images/8.png)
</br>
*modificaremos el nombre del archivo ost-sampleconfig.php por ost-config.php*
![](images/9.png)
</br>
![](images/10.png)
</br>
*una vez echo eso ya nos dejaria ir al siguiente paso*

###instalación###

*nos saldría la siguiente pantalla y pondremos lo que querramos\(como el email el idioma y el usuario Admin\).*
![](images/11.png)
</br>
*Y aqui configuraremos la base de datos.*
![](images/12.png)
</br>
*Despues nos sale este error que se soluciona de la siguiente manera:*
![](images/15.png)
</br>
*Vamos al panel de xammpp y pulsamos en el config de mysql*
![](images/16.png)
</br>
*Dentro del fichero, añadiriamos la siguiente linea:*
![](images/17.png)
</br>
*Y ya habriamos terminado solo faltarian los permisos\(en mi caso estoy en windows asi que ire a la ruta de osticket y desde powershell les dare permisos\)*
![](images/13.png)
</br>
*le dariamos los permisos desde powershell*
![](images/24.png)
</br>
*Una vez echo eso ya tendriamos el osticket instalado y configurado*
![](images/14.png)
</br>

###¿Como funciona?###
*accedemos al panel del administrador del xampp que es la siguiente ruta:*
![](images/18.png)
</br>
*si nos fijamos aqui ya tenemos el panel de adminisrador*
![](images/19.png)
</br>
*crearemos un usuario*
![](images/25.png)
</br>
*Y lo añadiremos*
![](images/26.png)
</br>
*Ya estaria Creado*
![](images/27.png)
</br>

###hacer y enviar un ticket###
*crearemos un ticket entrando a la siguiente ruta y dandole a "open a new ticket"*
![](images/20.png)
</br>
*Como lo hize sin registrarme,\(tambien lo puedes hacer en modo sin log in\), me pide que inserte el correo, nombre, numero de telefono y que reporte el Help Topic y una descripción*
![](images/21.png)
</br>
*Y aqui vemos que lo envio el usuario prueba Melián que es Guest"invitado" el dia la hora y el reporte*
![](images/22.png)
</br>
*Pulsamos encima del ticket y nos salen los detalles. El número de ticket, Ultima actualización, el estado, el asunto\(que fue el que escribi anteriormente\), el departamento y la asignación *
![](images/23.png)
</br>