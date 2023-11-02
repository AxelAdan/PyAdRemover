# PyAdRemover

## Descripción
PyAdRemover es un proyecto de software en Python que remueve anuncios (publicidad) que estén en el tráfico de una red. Utiliza técnicas de análisis de paquetes y filtrado de contenido para detectar y bloquear los anuncios no deseados.

## Objetivo
El objetivo de este proyecto es proporcionar una solución eficaz y sencilla para mejorar la experiencia de navegación web de los usuarios, eliminando los anuncios intrusivos y molestos que pueden afectar su privacidad y seguridad.

## Funcionalidad
PyAdRemover funciona como un proxy entre el navegador web del usuario y los servidores web. Intercepta las solicitudes y respuestas HTTP/HTTPS y analiza su contenido para identificar los anuncios. Si encuentra algún anuncio, lo reemplaza por un espacio vacío o un mensaje personalizado. PyAdRemover también permite al usuario configurar una lista blanca de sitios web o dominios que no desea filtrar, así como una lista negra de sitios web o dominios que desea bloquear completamente.

## Requisitos
Para ejecutar PyAdRemover se necesita:

- Python 3.9 o superior
- Las siguientes librerías de Python: requests, scapy, beautifulsoup4, lxml
- Un navegador web compatible con proxy HTTP/HTTPS

## Uso
Para usar PyAdRemover se debe:

- Abrir una terminal y navegar hasta la carpeta del proyecto
- Ejecutar el siguiente comando: python pyadremover.py
- Configurar el navegador web para usar el proxy local en el puerto 8080
- Navegar por la web sin anuncios

## Licencia
PyAdRemover está licenciado bajo la licencia MIT. Consulte el archivo LICENSE para más detalles.

## Contribución
Si desea contribuir al desarrollo de PyAdRemover, puede hacerlo mediante:

- Reportar errores o sugerir mejoras en la sección de issues del repositorio

## Contacto
Si tiene alguna pregunta o comentario sobre PyAdRemover, puede contactarme mediante:

- Instagram: [@adan_axel](https://www.instagram.com/adan_axel)
