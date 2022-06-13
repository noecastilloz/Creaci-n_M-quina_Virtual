##Creación de dos Máquinas virtuales una dentro de la otra.

![logo personal](https://github.com/noecastilloz/Creaci-n_M-quina_Virtual/blob/main/imagenes.py/Mi%20logo1.png)

**Requisito**

Computadora
Tener cuenta de Azure
Descargar escritorio remoto de Microsoft en la Microsoft store

************************************************

##Intrucciones

1.- Entras con tu usuario y contraseña al portal de Azure en la ventana principal buscas el icono de Máquinas Virtuales si no esta lo tecleas un su buscador de recursos.

![inicio](https://github.com/noecastilloz/Creaci-n_M-quina_Virtual/blob/main/imagenes.py/1.jpg)

Una vez seleccionado Máquinas virtuales se abre una ventana nueva como esta.

![VM](imagenes.py\2.jpg)

2.- Estando en la ventana de Máquinas virtuales le damos en crear y se nos desplegara un menú y seleccionamos la primera opción.

![](imagenes.py\3.jpg)

3.- Y se nos abre una nueva ventana en la cual llenaremos los siguientes campos
Por default de la suscripción tal como esta
Grupo de recursos le asignamos un nombre
Nombre de la máquina virtual
Opciones de disponibilidad la dejamos por default
Zona disponible la dejamos como esta Y se nos abre una nueva ventana en la cual llenaremos los siguientes campos.

3a ![](imagenes.py\3a.jpg)

3b En el campo dónde seleccionamos la región tenemos que seleccionar una en donde no nos limite, en las siguientes imágenes vemos que una nos indica esta leyenda "El tamaño no esta disponible actualmente en eastus2 para la suscripción" esto pasa con la cuenta de estudiante.

![](imagenes.py\3b.jpg)

3c Una vez seleccionada la región correcta se tendría que ver así.

![](imagenes.py\3c.jpg)

4.- Una vez corregido el problema de la región procedemos con los siguientes campos que son:
Seleccionar la imagen del SO que podemos emplear, se despliega un menú con los SO que están disponibles, en mi caso seleccionare W10  y en la segunda máquina virtual que se cree seleccionare W11.  

![](imagenes.py\4.jpg)

5.- Creamos la cuenta de administrador y en reglas de puerto de entrada lo dejamos como esta muy importante de estar RDP (Remote Desktop Protocol), y al final marcamos la casilla de la licencia de W10.

![](imagenes.py\5.jpg)

6.- Una vez que se hayan llenado todos los campos requeridos le damos en revisar y crear.
Si no marca ningún error tiene que verse así y le damos en crear.

![](imagenes.py\6.jpg)
![](imagenes.py\7.jpg)
![](imagenes.py\8.jpg)

EXITO 👏👏👏👏👏👏

7.-estos mismos pasos se hacen nuevamente para crear la segunda máquina virtual, y antes de seleccionar revisar y crear nos dirigimos a redes Y hacemos lo siguiente validamos que en la opción de red virtual este el nombre del grupo de la primera máquina virtual con terminación “vnet”

![](imagenes.py\9.jpg)

![](imagenes.py\10.jpg)

##Puesta en marcha las dos Máquina Virtuales.

1.- Descargar de Micrsoft store el programade de escritorio remoto de Microsoft

![](imagenes.py\11.jpg)

2.- 
