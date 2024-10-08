# 0373-A2-JunhaoXiang
0373-A2-JunhaoXiang

# Evaluación inicial

1. ¿Qué es una página web?
   
    Es un documento electrónico accesible a través de internet que contiene información organizada y presentada de forma visual.

2. ¿Qué es un servidor web?
   
    Es un sistema que almacena y entrega páginas web a los navegadores cuando los usuarios las solicitan, usando protocolos como HTTP o HTTPS.

3. ¿Qué son los lenguajes de marcas? ¿Cuántos conoces?. 

    Son sistemas basados en etiquetas que definen la estructura y formato de documentos, usados para organizar datos y controlar la presentación de información en páginas web o archivos de texto.
   
    |Nombre | Enlace a documentación | 
    |-----------|--------------------|
    |HTML |[HTML](https://es.wikipedia.org/wiki/HTML "HTML")|
    |XML |[XML](https://es.wikipedia.org/wiki/Extensible_Markup_Language "XML")|
    |Markdown |[Markdown](https://es.wikipedia.org/wiki/Markdown "Markdown")|
    |YAML |[YAML](https://es.wikipedia.org/wiki/YAML "YAML")|


   
4. ¿Qué es HTML ? ¿Sabes cómo se estructura?

    (HyperText Markup Language) es el lenguaje estándar para crear y estructurar páginas web. Utiliza etiquetas para organizar contenido, como textos, imágenes y enlaces.

    ```
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>

    </body>
    </html>
        
    ```
    Figura 1: Estructura de código HTML
   
5. ¿Qué es CSS?
   
    Es uno de los lenguajes más importantes que se utilizan para ordenar las instrucciones referentes a la apariencia de un sitio y presentar los contenidos de una página de forma atractiva.

6. ¿Sabes cómo funciona un navegador web? Describe brevemente el proceso que se sigue para visualizar una página web.:
* __Solicitud:__ El usuario ingresa una URL en el navegador.
* __Resolución DNS:__ El navegador convierte el nombre del dominio en una dirección IP del servidor que aloja la página.
* __Conexión al servidor:__ El navegador envía una solicitud HTTP/HTTPS al servidor web correspondiente.
* __Respuesta del servidor:__ El servidor envía los archivos de la página (HTML, CSS, JavaScript, imágenes, etc.) al navegador.
* __Renderización:__ El navegador interpreta el código recibido y construye la página para mostrarla visualmente al usuario.

![Esquema de peticiones HTML](Esquema%20de%20peticiones%20HTML.png "Esquema de peticiones HTML")

Figura 2: Esquema de peticiones HTML