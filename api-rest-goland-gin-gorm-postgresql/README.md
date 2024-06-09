# Tutorial de Go - UNAL

Cordial saludo lector, este aporte por parte del grupo de estudio encargado de la parte practica de Go, es una API totalmente funcional y contenerizada, la cual se encarga de realizar operaciones CRUD sobre una base de datos PostgresSQL, para ello se utilizo el framework Gin y el ORM GORM.

Todo esto fue posible gracias al creador de la API **tutofox.com** desarollador y creador de contenido, el cual desarrollo esta API, como aporte nosotros realizamos unos ajustes en terminos de configuración y dockerización, para hacer posible llegar a ustesdes un proyecto totalmente funcional y listo para ser desplegado en cualquier entorno, de manera sencilla y rapida.

**Gracias por su atención y esperamos que este aporte sea de su agrado.**

# Instrucciones de instalación y despliegue

1. Tener instalado Docker y Docker Compose en su maquina.
   
2. Tener instalado Git en su maquina.
   
3. Tener un editor de texto o IDE para poder visualizar el código.
   
4. Si esta usando Windows, tener instalado WSL2 y una distribución de Linux.
   
5. En la terminar de su distribución de Linux, ingresar el siguiente comando para instalar Docker y Docker Compose, desde la ubicación del proyecto:
```bash
sudo docker-compose up --build
```
1. Una vez realizado el paso anterior, podra visualizar la documentación de la API, al importar ela archivo **test de Go.postman_collection.json** en Postman.
   
2. Para detener la ejecución de la API, en la terminal de su distribución de Linux, presione **Ctrl + C** y luego ejecute el siguiente comando:
```bash
sudo docker-compose down
```