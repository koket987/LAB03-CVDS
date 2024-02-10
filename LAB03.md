LABORATORIO 3 – TDD

LASES DE EQUIVALENCIA

CREAR UN PROYECTO CON MAVEN

En el directorio de trabajo ejecutar el comando necesario para crear/generar un proyecto maven basado en un arquetipo:

![](Aspose.Words.95934d8d-0411-4c52-8123-e48cf9e2a226.001.png)

ACTUALIZAR Y CREAR DEPENDENCIAS EN EL PROYECTO

Busque en internet el repositorio central de maven.

![C:\Users\santiago.rodriguez-s.LABINFO\AppData\Local\Microsoft\Windows\INetCache\Content.MSO\E05E881F.tmp](Aspose.Words.95934d8d-0411-4c52-8123-e48cf9e2a226.002.png)

![C:\Users\santiago.rodriguez-s.LABINFO\AppData\Local\Microsoft\Windows\INetCache\Content.MSO\A7346685.tmp](Aspose.Words.95934d8d-0411-4c52-8123-e48cf9e2a226.003.png)

![C:\Users\santiago.rodriguez-s.LABINFO\AppData\Local\Microsoft\Windows\INetCache\Content.MSO\96A0DFDB.tmp](Aspose.Words.95934d8d-0411-4c52-8123-e48cf9e2a226.004.png)

![C:\Users\santiago.rodriguez-s.LABINFO\AppData\Local\Microsoft\Windows\INetCache\Content.MSO\E5A7E1A1.tmp](Aspose.Words.95934d8d-0411-4c52-8123-e48cf9e2a226.005.png)


Busque el artefacto JUnit y entre a la versión más nueva. imagen

Ingrese a la pestaña de Maven y haga click en el texto de la dependencia para copiarlo al portapapeles.

Edite el archivo pom.xml y realice las siguientes actualizaciones:

Agregue/Reemplace la dependencia copiada a la sección de dependencias.

Hay que cambiar la versión delcompilador de Java a la versión 8, para ello, agregue la sección properties antes de la sección de dependencias:

![C:\Users\santiago.rodriguez-s.LABINFO\AppData\Local\Microsoft\Windows\INetCache\Content.MSO\C33B3557.tmp](Aspose.Words.95934d8d-0411-4c52-8123-e48cf9e2a226.006.png)



![](Aspose.Words.95934d8d-0411-4c52-8123-e48cf9e2a226.007.png)

COMPILAR Y EJECUTAR

Ejecute los comandos necesarios de Maven, para compilar el proyecto y verificar que el proyecto se creó correctamente y los cambios realizados al archivo pom no generan inconvenientes.

Busque el comando requerido para ejecutar las pruebas unitarias de un proyecto desde Maven y ejecútelo sobre el proyecto. Se debe ejecutar la clase AppTest con resultado exitoso.

![C:\Users\santiago.rodriguez-s.LABINFO\AppData\Local\Microsoft\Windows\INetCache\Content.MSO\A562E07D.tmp](Aspose.Words.95934d8d-0411-4c52-8123-e48cf9e2a226.008.png)


