**Integrantes** 

Jonathan Andres Vanegas Herrera 

Karen Yulieth Rodríguez Baez

Fabian David Merentes Fraile

**Herramientas Utilizada**

- Máquina virtual usando la página Digital Ocean
- Máquina virtual con Ubuntu 18.04 (LTS) x64
- Docker versión 20.10.7
- Jenkins versión 2.361.3
- Visual studio code
- Node versión 16.13.1
- Angular CLI versión 14.2.9 
- GitHup

**¿Que hace la aplicación?**

Es una plataforma web implementada con angular, es una interfaz gráfica muy sencilla cuenta con una estructura de HTML y estilos css e incluye unos datos. Es una introducción básica a DevOps y poder ser implementado en proyectos más grandes.

**Instrucciones.**

Primero que todo una vista de lo que es la plataforma Web de producción. 

![](Aspose.Words.b56932c9-0769-40bb-b4cf-e19b37a0eedd.001.png)

**Pasos para hacer DevOps**

1. Realizamos un cambio en el código por medio de visual studio code. En este caso se va a cambiar el color de fondo de la página Web y procedemos a guardar los cambios. 

![](Aspose.Words.b56932c9-0769-40bb-b4cf-e19b37a0eedd.002.png)

1. Ahora necesitamos guardar estos cambios directamente en el GitHup, por medio de la terminal con los siguientes comandos o instrucciones. 
   1. Git int
   1. Git add .
   1. Git commit -m “Cambio de color”
   1. Git push

![](Aspose.Words.b56932c9-0769-40bb-b4cf-e19b37a0eedd.003.png)

1. Vamos a ver el proceso de despliegue en el Jenkins que esta alojada en la ip 147.182.206.150 la cual es proporcionado por digital ocean donde montamos la maquina virtual 

![](Aspose.Words.b56932c9-0769-40bb-b4cf-e19b37a0eedd.004.png)

y el puerto 8080 el cual fue instalado con la imagen de Jenkins-chrome en el contenedor de Docker por medio del siguiente comando.

![](Aspose.Words.b56932c9-0769-40bb-b4cf-e19b37a0eedd.005.png)

Entonces procedemos a ingresar a Jenkins a el navegador 

![](Aspose.Words.b56932c9-0769-40bb-b4cf-e19b37a0eedd.006.png)

1. seleccionamos el pipeline que en este caso se llama tallar DevOps en este apartado podemos ver el proceso de despliegue.

![](Aspose.Words.b56932c9-0769-40bb-b4cf-e19b37a0eedd.007.png)






![](Aspose.Words.b56932c9-0769-40bb-b4cf-e19b37a0eedd.008.png)

1. Ya por último procedemos a ver los cambios en la pagina web de Producción.

![](Aspose.Words.b56932c9-0769-40bb-b4cf-e19b37a0eedd.009.png)
