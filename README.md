# Tensor de tensiones de Cauchy — laboratorio 3D

Aplicación interactiva de mecánica de medios continuos para visualizar el tensor simétrico de tensiones en tres dimensiones y el vector de tracción de Cauchy sobre planos con orientación variable.

**Autor:** Francisco Goitia · francisco.goitia@upc.edu

## Abrir la aplicación

- **En línea:** después de activar GitHub Pages, visitar https://fragoi95.github.io/tensor_app/
- **Sin conexión:** descargar `index.html` y abrirlo en el navegador.

No utiliza dependencias externas ni requiere instalación.

## Publicación mediante GitHub Pages

En este repositorio ir a **Settings → Pages → Build and deployment**. Seleccionar **Deploy from a branch** y, como origen, **main / (root)**. Guardar. La dirección prevista es https://fragoi95.github.io/tensor_app/

## Qué representa

Seis componentes independientes de un tensor simétrico, valores de la matriz actualizados en directo, vectores de Cauchy en una esfera, selección de la normal al plano, descomposición normal y tangencial, tensiones principales y von Mises.

Convención de signos: tensión normal de tracción positiva y de compresión negativa. El término «vector de tracción de Cauchy» describe la fuerza superficial por unidad de área de cualquier signo.

## Sobre la visibilidad del código

GitHub Pages sirve archivos web estáticos al navegador. Cualquier persona que acceda al sitio puede inspeccionar o descargar el HTML, CSS y JavaScript, aunque se minifiquen u ofusquen. Comprimirlos en ZIP tampoco ofrece protección. Para ocultar algoritmos se requiere ejecutarlos en un servidor, manteniendo en el navegador solo la interfaz visual.

