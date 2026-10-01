PDF Document Studio
Vega Document Studio es una aplicación web de una sola página para visualizar documentos PDF y EPUB y realizar anotaciones y modificaciones visuales sobre archivos PDF. Está diseñada para ejecutarse directamente en el navegador, sin necesidad de instalar un programa.
Características
Documentos PDF
Abrir y visualizar archivos PDF.
Navegar entre páginas y ajustar el nivel de zoom.
Buscar texto y desplazarse entre las coincidencias encontradas.
Resaltar texto y añadir subrayados.
Añadir texto sobre el documento.
Sustituir visualmente texto existente mediante una cobertura y una nueva capa de texto.
Añadir campos de texto superpuestos para rellenar documentos.
Crear una firma dibujándola y colocarla en el PDF.
Seleccionar, mover y redimensionar las anotaciones añadidas.
Personalizar el texto con tamaño, tipografía, negrita, cursiva y color.
Guardar y exportar el documento PDF editado.
Documentos EPUB
Abrir y leer libros electrónicos en formato EPUB desde la aplicación.
Privacidad y funcionamiento
Los documentos se procesan localmente en el navegador.
No es necesario subir los documentos a un servidor para visualizarlos o editarlos.
Se requiere conexión a Internet para cargar las bibliotecas externas utilizadas por la aplicación.
Uso
Descarga o guarda el archivo HTML de Vega Document Studio.
Abre `vega_document_studio_fondo_suave_v7.html` con un navegador moderno, como Google Chrome o Microsoft Edge.
Pulsa Abrir PDF o EPUB y selecciona el documento.
Utiliza las herramientas de la interfaz para leer, buscar o añadir anotaciones.
Cuando termines de editar un PDF, utiliza la opción de guardado o exportación para generar el archivo resultante.
> Para un funcionamiento correcto, mantén la conexión a Internet mientras se carga la aplicación, ya que las bibliotecas se obtienen desde CDN.
Tecnologías utilizadas
HTML5: estructura de la aplicación.
CSS3: diseño adaptable e interfaz.
JavaScript: lógica e interactividad.
PDF.js 3.11.174: visualización y lectura de documentos PDF.
pdf-lib 1.17.1: generación y exportación de PDF.
EPUB.js 0.3.93: lectura de libros EPUB.
Las bibliotecas PDF.js, pdf-lib y EPUB.js se cargan desde cdnjs.
Limitaciones conocidas
La sustitución de texto es una modificación visual: cubre el texto original y coloca texto nuevo encima. No cambia el texto interno original del PDF.
Los campos de formulario añadidos son elementos superpuestos; no se convierten en campos AcroForm nativos.
La búsqueda puede no encontrar una frase si el PDF la almacena dividida en varios fragmentos de texto.
La lectura y edición dependen de que el navegador pueda cargar las bibliotecas externas.
La compatibilidad y el aspecto de algunos PDF pueden variar según cómo se haya creado el documento.
Estructura del proyecto
El proyecto puede utilizarse como un único archivo:
```text
Vega-Document-Studio/
└── vega_document_studio_fondo_suave_v7.html
```
Este archivo contiene la interfaz, los estilos y la lógica de la aplicación. Las bibliotecas de terceros se cargan externamente.
Licencias
Vega Document Studio es el nombre de esta aplicación. Las bibliotecas de terceros utilizadas mantienen sus propias licencias y condiciones:
PDF.js: https://github.com/mozilla/pdf.js
pdf-lib: https://github.com/Hopding/pdf-lib
EPUB.js: https://github.com/futurepress/epub.js
Antes de redistribuir una copia de la aplicación, revisa las licencias y condiciones aplicables a cada dependencia.
Versión
Versión documentada: V7
Nombre: Vega Document Studio
Formato: aplicación web de archivo único (`.html`)
