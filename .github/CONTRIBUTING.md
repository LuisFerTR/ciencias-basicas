# Guía de contribución
Gracias por tu interés en este proyecto, para contribuir necesitarás una cuenta en [Github](https://github.com/join?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)
y tener instalado [git](https://git-scm.com/) en tu equipo. Una vez que hayas cumplido con esos dos requisitos los pasos a seguir son:
## Hacer un fork al proyecto
Haz un fork de este repositorio haciendo click en el botón "Fork" ubicado en la parte superior derecha de este sitio.
![alt fork](https://i.ibb.co/588jhjt/fork.png)
## Clonar el repositorio
Dirígete al fork del repositorio que se encuentra en tu cuenta y da clic en el botón "Code", se desplegará una pequeña ventana copia el enlace que muestra la ventana.

![alt clonar](https://i.ibb.co/7tr5qTW/clone.png)

Después abre tu terminal o consola y escribe la instrucción:
``` 
git clone [enlace que acabas de copiar]
```
La instrucción final debe quedar así:
``` 
git clone https://github.com/tuNombreUsuario/ciencias-basicas.git
```
Reemplazando "tuNombreUsuario" por el nombre de tu cuenta de Github.
Esta instrucción descargará el proyecto en tu computadora.
## Crear una rama(branch)
En tu consola cámbiate al directorio del proyecto, si es que no estás ya en él.
```
cd ciencias-basicas
```
Crea una rama donde harás los cambios al proyecto.
```
git checkout -b [tuNombreUsuario]-[materia]
```
Estos son los contenidos aceptados en "materia" por el momento:
- diferencial
- integral
- vectorial
- ecuaciones
- lineal

Por ejemplo si quisiera agregar material de algebra lineal mi rama debería llamarse `LuisFerTR-lineal`.

El siguiente paso es agregar los archivos al directorio ciencias-basicas/[materia].

O si tu aporte es el enlace de un artículo o una playlist de videos el paso a seguir es editar el README de la carpeta de la materia de tu aporte y agregar en la sección correspondiente el noombre del tema a agregar entre corchetes([]) y entre paréntesis el enlace del recurso, es importante agregar el tema en orden alfabético.
En la siguiente imagen se muestra un ejemplo:
![alt Editar Readme materia](https://i.ibb.co/TMJMbP2/readme.png)

Después se utiliza la siguiente instrucción que añadirá los archivos listos para el commit:
```
git add .
```
Y luego:
```
git commit -m "[Tema del material]"
```
Esto guardará los cambios en el repositorio local, antes de añadirlos al remoto se utiliza la instrucción, para asegurar que tienes tu repositorio actualizado y evitar conflictos:
```
git pull --rebase main
```
Y para subirlos al remoto se usa:
```
git push origin [tuNombreUsuario]-[materia]
```
Si recargas la página de tu fork aparecerá el siguiente recuadro
![alt compare](https://i.ibb.co/M86fCSN/compare.png)

Deberás dar clic en el botón verde y te llevará a la siguiente ventana donde deberás llenar los campos y dar clic en el botón verde.
![alt pull request](https://i.ibb.co/nQb18Jy/pullrequest.png)

Por último queda esperar que aprueben tu pull request.
Gracias por colaborar :D
