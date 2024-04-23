---
layout: post
title:  "Tutorial Markdown 2"
date:   2022-09-13 01:05:58 +0200
categories: jekyll update
---

# Este es mi primer post sobre markdown.

### En este post os explicare las formas de escribir en markdown.

## Ahora mediante una lista os dire las etiquetas que trataremos.

1.- Elementos de línea :   
    - Énfasis.   
    - Links o enlaces.   
    - Código.   
    - Imágenes.   
___

# 1.- Elementos de linea:

## Enfasis (negritas y cursivas)Markdown utiliza asteriscos o guiones bajos para enfatizar.

Simplemente tendrás que envolver palabras o textos en éstos símbolos para conseguir cursivas o negritas.

*cursiva*
_cursiva_
**negrita**
__negrita__

Por supuesto si quieres utilizar los dos tipos de énfasis no tienes más que combinar la sintaxis, envolviendo la palabra entre tres asteriscos o tres guiones bajos.

***cursiva y negrita***
___cursiva y negrita___

___

## Links o enlaces:

Añadir enlaces a una publicación, más que común, hoy en día es algo casi obligatorio. Con Markdown tendrás varias formas de hacerlo.

Links o enlaces en línea

Son los enlaces de toda la vida. Como su nombre indica, se encuentran en línea con el texto.
Se crean escribiendo la palabra o texto enlazada entre [] corchetes, y el link en cuestión entre () paréntesis.
[enlace en línea](http://www.limni.net)

Links o enlaces como referencia

La desventaja del método anterior, es que si utilizas links demasiado complejos o largos pueden dificultarte la lectura de tu texto.

Para solucionarlo y crear tu contenido de una manera más ordenada puedes generar enlaces de referencia.

Esto quiere decir que en tu texto enlazarás palabras o códigos concretos (formados por letras y/o números), que en otro lugar más apartado de tu documento tendrás definidos como determinadas URL.

[nombre que quieres darle a tu enlace][nombre de tu referencia]
[nombre de tu referencia]: http:www.tuenlace.com

La referencia [nombre de tu referrencia] puede estar incluida en cualquier parte del documento, así puedes organizarte mejor y de una manera más limpia, recopilando todas tus referencias en un mismo lugar.

Además como ves a continuación, esta referencia no se incluye en el resultado final, sino que desaparece.

«Me llamo Javier Cristóbal y tengo un blog sobre productividad mac.

En dicha web recopilo artículos sobre todo lo relacionado con automatización, gestión y eficiencia.»

___

## Codigo:

En según que tipo de publicaciones (sobre todo las de carácter técnico), necesitarás añadir pequeñas secciones donde mostrar código de otro lenguaje, atajos de teclado, o demás contenido que no debería ser tratado como tal.

Para ello tienes disponible dos alternativas.

Código puro 

La forma más sencilla de escribir código en Markdown es envolver el texto entre dos comillas sencillas `.

`Esto es una línea de código`

Como ves, es muy útil para introducir código dentro de la misma línea o párrafo, algo que no permite el método siguiente.

Texto preformateado

La otra manera de añadir código en Markdown es comenzar el párrafo con cuatro espacios en blanco.
Ojo, ¡estos espacios deberás incluirlos en cada línea que escribas! Para añadir código en bloque es mejor utilizar la sintaxis que viste anteriormente: códigos de bloque.

___

## Imagenes:
Insertar una imagen con Markdown se realiza de una manera prácticamente idéntica a insertar links.

Solo que en este caso, deberás añadir un símbolo de ! exclamación al principio y el enlace no será otro que la ubicación de la imagen.

![Texto alternativo](/ruta/a/la/imagen.jpg)
El texto alternativo es lo que se mostraría si la carga de la imagen fallase.

También podrás añadir un título alternativo entrecomillándolo al final de la ruta. Esto sería el título mostrado al dejar el cursor del ratón sobre la imagen.

![Texto alternativo](/ruta/a/la/imagen.jpg "Título alternativo")
Ya que al añadir imágenes también estás tratando con URLs, puedes utilizar el método que viste anteriormente para incluir links mediante referencias, solo que en este caso los enlaces de referencia serán aquellos donde se encuentre tu imagen.

De esta forma podrías insertar una imagen  
![nombre de la imagen][img1]  
O dos, sin ensuciar tu espacio de escritura.  
![nombre de la imagen2][img2]  
[img1]: /ruta/a/la/imagen.jpg "Título alternativo"  
[img2]: /ruta/a/la/imagen2.jpg "Título alternativo" 
___
