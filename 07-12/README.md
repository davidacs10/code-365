# Practicando CSS GRID

## Fundamentos de CSS GRID

display:grid; de esta forma decimos que el contenedor va a ser una grid o una rejilla.

grid-template-columns: con esta propiedad vamos a especificar el tamaño que queremos que tenga cada columna.

grid-template-rows: con esta propiedad vamos a especificar el tamaño que queremos que tenga cada fila.

gap: sirve para poner unos espaciados entre cada uno de los elementos.

fr: significa que podemos crear nuestras columnas de manera que si ponemos 1fr se creara una unica columna en el contenedor, si ponemos 1fr 1fr crearemos 2 columnas y asi sucesivamente. Tambien podemos combinar esas unidades de acuerdo a lo que necesitemos. Si queremos que la primera columna sea de 200px y la siguiente de 1fr se puede hacer sin problemas. Tambien puedes probar usando esta combinacion de fr que seria 1fr 2fr 1fr y asi podras distribuir tus columnas en grid de acuerdo a tus gustos.

## Medidas minimas y maximas

En este caso podremos usar las propiedades grid-template-columns y grid-template-rows con la unidad minmax() de acuerdo a lo que queramos en nuestra celda. Por ejemplo, con esta unidad podremos establecer un tamaño minimo y un tamaño maxmimo a nuestras columnas y celdas separados por una coma

### Ejemplo minmax()
grid-template-columns: minmax(200px, 1fr) 200px; Con esta propiedad vamos a establecer que el minimo de la primera columna van a ser 200px, es decir, que menos de eso no podra estar. Y el maximo de 1 fraccion. Es decir que ocupara el espacio necesario sin perjudicar a los 200px de la siguiente columna.

## Notas