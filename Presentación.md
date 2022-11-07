---
marp:  true
author: EquipoH
size: 16:9 
theme: gaia
backgroundImage: url('https://marp.app/assets/hero-background.svg')
---
# Introducción a Markdown
![bg right:50% w:500](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1200px-Markdown-mark.svg.png)

---
# ¿Qué es Markdown?
* Markdown es un lenguaje de marcado ligero que permite añadir elementos de formato a documentos de texto. 

![Imagen de la UI bg right:50% w:500](https://static.platzi.com/media/user_upload/markdown-e22ab125-1b09-442f-a767-82b3408264ee.jpg)

---
# Formateo de texto
Se puede enriquecer el texto mediante _itálicas_ y **negritas**.
Para convertir a itálicas se usan los "_". Por ejemplo: 
`_Este texto está en itálicas_`  produce el siguiente resultado:

_Este texto está en itálicas_

Para convetir a negritas, se usan los "**". Por ejemplo:
`** Este texto está en negritas**`  produce el siguiente resultado:

**Este texto está en negritas**

---
# Enumeración de elementos
En MarkDown existen dos formas de enumerar elementos:

### - Listas no ordenadas

### - Listas ordenadas

---
## Listas no ordenadas
Estas listas se crean mediante los símbolos "*, -, +"
`+ Esto es una lista` produce:
+ Esto es una lista

`* Esto es una lista` produce:
* Esto es una lista
---
## Listas ordenadas
Estas listas indiferentemente de los números que contenga, deben comenzar en 1.
`1. Item a `
`1. Item b`
`1. Item c` tienen como salida:
1. Item a
1. Item b
1. Item c

---
# Imágenes
Para insertat imágenes es necesario la URL de dicha imagen así como el texto alternativo que la acompaña. La sintaxis es de la siguiente forma
`![Título de la imagen](url.png)`

Existen ciertos modificadores que permiten mayor personalización a las imágenes, de los cuales destacan:
* **width:** ancho de la imagen
* **height:** alto de la imagen

---
# Código
Para trabajar con código se necesitan "``".

` ``Esto es una línea de código`` ` tiene la siguiente salida:

`Esto es una línea de código`

---
# Uso de Markdown
Una de las formas de trabajar con Markdown es con Marp, una extensión disponible en Visual Studio Code.
Para su instalación se debe hacer lo siguiente:

`Extensiones > Buscar > "Marp" > Instalar`
![bg right:50% height:400px](https://raw.githubusercontent.com/marp-team/marp-vscode/main/docs/screenshot.png)