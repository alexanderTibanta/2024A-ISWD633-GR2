# COMPLETAR  
Comparando sus conocimientos antes de hacer la práctica con sus conocimientos después de hacer la tarea, explicar los principales aprendizajes logrados para beneficio de su formación profesional.  
Si solucionó un problema presentado al realizar la práctica también se debe documentar.

Tras realizar la practica se tiene en consideracion la adquisicion de nuevos conocimientos en relacion al uso de imagenes de Docker, pues hace más sencillas las instalaciones y las configuraciones sin tener que estar preocupándonos por las dependencias, ademas, una imagen es un archivo único que contiene librerías, dependencias y configuraciones necesarias para instalar, ejecutar una aplicación o un conjunto de aplicaciones.

Ademas, un contenedor de Docker es una imagen de Docker instanciada (en ejecución), de esta forma, en esta practica se realizo la creacion, enlistado, detencion y eliminacion de contenedores

Por ultimo, se obtuvo onocimiento para el mapeo de puertos para redirigir el tráfico del puerto especifico del contenedor al puerto especifico en el host. De esta manera, cuando accedas a http://localhost:#### en tu navegador, el tráfico se dirigirá al servidor web dentro del contenedor en el puerto especifico.

Observaciones: Para esta practica solo se realizo un cambio en relacion al uso del comando docker images | grep hello-world el cual se debio remplazar debido al entorno de trabajo por docker images | findstr "hello-world"
