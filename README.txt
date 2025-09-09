EJECUTAR
el archivo 'jugarki.py'0 es un script de python
hay que tener instalado python y las librerias del script
el archivo 'run.bat' es un ejecutable de windows que ejecuta el script de python
FUNCIONAMIENTO
basicamente el script usa el microfono para escuchar notas musicales
usando analisis de fourier logra determinar que nota esta sonando
por ejemplo do3 'C3'
y usando la libreria 'keyboard' presiona una tecla del teclado
cuando se escucha una nota determinada.
la idea es que estas teclas sean las que se configuran en el emulador de snes
TRAMPA
en este juego es dificil presionar cosas como ->-> ya que la parte que
determina la nota que suena se demora mucho, por lo que en ciertas teclas
solo es necesario tocar una vez una nota musical para que el boton se
presione dos veces, algo asi como un boton de turbo.