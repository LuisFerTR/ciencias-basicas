# Guía de contribución
Gracias por tu interés en este proyecto, para contribuir necesitarás una cuenta en [Github](https://github.com/join?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)
y tener instalado [git](https://git-scm.com/) en tu equipo. Una vez que hayas cumplido con esos dos requisitos los pasos a seguir son:
## Hacer un fork al proyecto
Haz un fork de este repositorio haciend click en el botón "Fork" ubicado en la parte superior derecha de este sitio.
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

