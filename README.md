# examenDAM
Para utilizarlo en el examen

Instrucciones:

Dentro de la pagina web de github:
  1) Creamos un repositorio en github
  1) Entramos en el repositorio que deseamos copiar
  2) Copiamos la url del repositorio
En consola:
  1) Nos posicionamos en el direcvtorio donde queremos clonar el    repositorio
  Ej: cd COD
  2) Clonamos el repositorio mediante el comando: git clone
  Ej: git clone -o examenDAM https://github.com/damiancastelao/examenDAM.git
  3) Subimos el repositorio clonado a nuestro repositorio de git hub
  eJ: git remote add origin https://github.com/LuciaPosada/Examen1Parte1.git
    git branch -M main
    git push -u origin main
  4) Entramos en el repositorio clonado
    Ej: cd examenDAM
  5) Hacemos los cambios que deseemos realizar
  6) Realizamos un git status para comprobar los cambios realizados
  7) Realizamos un git add a los ficheros que queramos añadir o hayn sufrido cambios
  8) Realizamos un git commit -m explicando los cambios realizados
  9) Subimos los cambios al repositorio mediante: git push origin main
