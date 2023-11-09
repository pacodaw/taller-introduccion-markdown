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
