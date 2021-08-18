# dataset

En este repositorio solo guardaremos la lista de fotografías con su latitud, longitud, y
orientación. Para la orientación podemos usar un vector `(x1, y1, x2, y2)` o un punto más una
rotación `(lat, lon, rot)`. El identificador de cada fotogría debe ser el código de referencia
proporcionado por el cdf, como `03531FMHGE` para la foto publicada en
https://cdf.montevideo.gub.uy/catalogo/foto/03531fmhge.

Pensando en la posibilidad de agregar ubicación a fotografías de otras colecciones (por ejemplo, la
Biblioteca Nacional tiene fotos de todo el país acá
http://190.64.49.78:8080/jspui/handle/123456789/3), el archivo `fotos.csv` tiene una columna
`origen` donde podemos indicar este dato.
