# taller-introduccion-markdown
Taller introductorio a la sintaxis Markdown.

**Etiquetas básicas de Markdown**

**Encabezados**

Esto es un ecabezado h1  

Esto es un encabezado h2  

Esto es un encabezado h3  

Esto es un encabezado h4  

Esto es un encabezado h5  

Esto es un encabezado h6  


 **Negrita y cursiva**  
 
**Texto en negrita con la etiqueta de asteriscos dobles**


__Texto en negrita con la etiqueta de barras bajas dobles__

  
*Texto en cursiva mediante aasteriscos*  

*Texto en cursiva mediante barras bajas*

  
**Resaltar un comando**

En esta frase estamos resaltado el comando `ls -la`.

  
**Bloques de código**

 Al inicio del bloque se puede indicar de forma opcional cuál es el tipo de contenido que contiene el bloque para resaltar las palabras reservadas cuando se renderice. Por ejemplo: bash, python, yaml, json, html, javascript, etc.  
 Para resaltar bloques de código utilizamos tres acentos graves al principio y final del bloque a resaltar  
```
sudo systemctl start apache2
```
```bash
#!/bin/bash
echo "Hola mundo"
```
```python
celsius = float(input('Introduce una temperatura en grados Celsius: '))
farenheit = (1.8 * celsius) + 32
print(f'La temperatura en grados Farenheit es: {farenheit}')
```
```yaml
version: '3'

services: 
  apache:
    build: ./apache
    ports: 
      - 80:80
    volumes:
      - ./src:/var/www/html
```
**Enlaces**  
[Enlace a la página web del IES Jaume II El Just](https://portal.edu.gva.es/iesjaumeeljust/)  

**Otra forma de gestionar enlaces**  
[1]: https://portal.edu.gva.es/iesjaumeeljust/  
[2]: https://github.com  

**Listas**  

**Listas desordenadas**  

* Item 1
* Item 2
* Item 3
* Item 4

**Listas desordenadas anidadas**  

* Item 1
  * Item 1.1
  * Item 1.2
* Item 2
  * Item 2.1
* Item 3
* Item 4

**Listas ordenadas**  

1. Item 1
2. Item 2
3. Item 3
4. Item 4

**Listas ordenadas anidadas**  

1. Item 1  
  1.1 Item 1.1  
  1.2 Item 1.2  
2. Item 2  
  2.1 Item 2.1  
3. Item 3  
4. Item 4

**Tablas**  
| Encabezado 1 | Encabezado 2 | Encabezado 3
| --- | --- | --- | ---  


| Fila 1.1 | Fila 1.2 | Fila 1.3  

| Fila 2.1 | Fila 2.2 | Fila 2.3  

| Fila 3.1 | Fila 3.2 | Fila 3.3  

**Citar textos**  

Este texto no es una cita.  

> Este texto daría como resultado una cita.
> 
**Comentarios**  
Para poner un comentario en Markdown y que su contenido no sea renderizado, se utiliza la misma sintaxis que los comentarios de HTML.  

Párrafo 1.

<!- Este texto es un comentario y no será renderizado -->

Párrafo 2.  













