##Git Branch Model

El git branch model es un modelo de trabajo en git, donde se tienen dos tipos  
de ramas, las ramas permanentes y las ramas temporales.  
Entre las ramas permanentes tenemos a master y develop.  
Entre las ramas temporales tenemos a feature, release y hotfix.

En la rama master se encuentra la versión del proyecto que estará en producción.

En la rama develop tenemos el proyecto en desarrollo.

En la rama feature se desarrollan las nuevas caracteristicas para la proxima version.  
Puede ramificarse de develop y fusionarse nuevamente en la misma.

La rama release, se utiliza cuando se han adquirido suficientes caracteristicas  
para un lanzamiento. En esta rama solo se realiza la correccion de errores y la  
documentacion correspondiente, para finalmente fusionarse con la rama master y  
etiquetarse como una nueva version del proyecto.

La rama hotfix esta destinada para la correccion de errores criticos en una  
version en produccion. Por lo tanto, puede ramificarse de la rama master y fusionarse  
en la misma y en develop.
