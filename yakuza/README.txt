EL PATIO MÁLAGA — CARTA DIGITAL v3

CORRECCIÓN IMPORTANTE
Esta versión NO usa fetch() para cargar menu.json. Por eso index.html funciona al abrirlo directamente desde el Explorador de Windows y también en Brackets.

ESTRUCTURA
- index.html: página principal.
- css/estilos.css: diseño.
- js/menu.js: contiene los datos y genera automáticamente las categorías y platos.
- datos/menu.json: copia editable/referencia de los datos.
- img/: fotografías.

FOTOS
La ruta de cada foto está indicada en cada producto. Ejemplo:
img/hamburguesas/petunia.webp

PORTADA
img/restaurante/hero.webp

AMBIENTE
img/restaurante/ambiente-1.webp

Puedes usar JPG mientras pruebas, pero si el archivo se llama hero.jpg debes cambiar la ruta correspondiente en el código. Para producción conviene convertir las fotos a WebP/AVIF y comprimirlas.

IMPORTANTE
La carta conserva la información extraída del PDF. Algunos precios del PDF están visualmente desalineados al extraerse como texto; antes de publicar conviene validar esos precios contra la carta original.
