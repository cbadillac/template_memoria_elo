Template para Memoria de Titulación *Ing. Civil Electrónica*
==========================================================

Este template tiene por caracterísica la división de capítulos en archivos diferentes gracias al paquete *subfiles*

## Modo de uso

### Agregar capítulo
Para agregar un capítulo nuevo, crear una carpeta para éste capítulo dentro de la carpeta *capitulos*, y dentro agregar el archivo .tex correspondiente.
El contenido básico del archivo debe ser el siguiente:

```
\documentclass[../../main.tex]{subfiles}
\begin{document}
   %% poner aqui el contenido
\end{document}
```

Luego, para finalizar, agregar lo siguiente al archivo *main.tex*

> ` \subfile{capitulos/nombre_carpeta_cap/cap_x} `

## Dudas, Consultas y/o Recomendaciones

Si hay un error en el formato, realiza un pull requesto o simplemente realiza un comentario en github.


