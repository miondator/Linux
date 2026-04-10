# Linux
Reporsitorio personal donde estaré mostrando mis avances en el conocimiento aprendido en cursos certificados por Cisco sobre linux desde lo escencial hasta lo más avanzado

# ¿Qué es Linux🐧y porque debo aprenderlo?
Linux es un sistema operativo que permite ejecutar programas y aplicaciones en distintos tipos de hardware, no solo en computadoras de escritorio o portátiles.

Su principal relevancia radica en su uso generalizado, ya que está presente en:

- Servidores web
- Dispositivos móviles Android
- Plataformas en la nube (Google, Amazon, etc.)
- Chromebooks y redes Cisco.

Se estima que más de la mitad de las páginas web en Internet se generan desde servidores Linux, lo que lo convierte en una habilidad muy valiosa, incluso para quienes nunca lo han usado directamente en su computadora.

## Linux y sus interfaces: GUI vs CLI

Linux ofrece tanto una interfaz gráfica de usuario (GUI) —como la que usas en smartphones o computadoras— como una interfaz de línea de comandos (CLI), que es más eficiente para tareas avanzadas.

Mientras la GUI es intuitiva y visual, la CLI permite mayor control y transparencia, siendo especialmente útil para administración de sistemas y resolución de problemas, ya que muestra exactamente lo que el sistema está ejecutando en tiempo real.

## Primer comando

En Linux la herramienta más poderosa que existe es la terminal y mediante la terminal se puede ejecutar prácticamente cualquier tarea, el primer comando de utilidad y que aprendí es `ls`, ¿para que sirve ese comando?
`ls` es el comando más básico y te permite visualizar los archivos existentes en la ruta actual que te encuentres, por ejemplo:

``` 
miondator@miondatorlap:~$ `ls`
Descargas   Escritorio  Música      Público  snap
Documentos  Imágenes    Plantillas  Vídeos
```

Es importante saber que se debe tener cuidado en como se escribe un comando ya que en Linux existe algo llamado `Upper-Lower Case`, es decir, aquí sí importa el como está escrito algo ya que son comandos especificos y siguen una instrucción acorde como está definido por quien haya creado el comando, por ejemplo, en el caso anterior de haber escrito `LS` en lugar de `ls` el comando hubiera arrojado un error ya que la terminal no hubiera reconocido el comando y no habría ejecutado ninguna tarea
