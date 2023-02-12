# kubernetes-course
Entorno para el curso de Kubernetes

# Ejercicios Curso de Kubernetes

Hay un repositorio diferente para cada parte del curso que debe ser entregado. Depende del ejercicio se debera subir o ficheros / imagenes o pdf.

# Environment - Entorno

Opcion 1: Maquina virtual Linux en Vmware o VirtualBox.  Instancia en cualquier provider cloud o uso de la terminal Linux con Docker y Kubernetes en su computadora. <br>

Opcion 2: Docker-desktop con docker y kubernetes <br>

Opcion 3: Instalar kubernetes con Kind, para ello debemos tener instalado docker en nuestra computadora o en la maquina virtual donde lo ejecutemos
<br>

# Prueba de herramienta docker y docker-compose

Una vez instalado ejecutando ``` docker run -ti -p 80:80 httpd:latest ``` puede comprobar como se puede desplegar un servidor httpd.

# Prueba de herramienta kubernetes y kubectl

Una vez instalado ejecutar: ``` kubectl cluster-info && kubectl get all --all-namespaces ```


# Envio de los ejercicios

Los ejercicios estan subidos Modulo por modulo, y tienen que subirlo tal en su fichero, en el caso de que tenga que crear un script, introducir los comandos dentro, en caso de que sea un fichero .yaml o .json subir estos ficheros.

# Acceso a Documentacion

Hay documentacion tanto en mis repositorios en github/crcasis o gitlab/crcasis. <br>
Hay documentacion en las páginas oficiales y siempre es interesante apoyarse en hub.docker.io

# Como subir el contenido al repositorio

```
repository="https://repository.example.git" 
git clone $repository
git add . 
git commit -m "ejercicios curso de docker"
git push
```

