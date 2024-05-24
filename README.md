# Version del curso
Version Actual: v1.2.2

# Cabeceras 
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de enfasis
- letra *italica* de la primer forma.
- letra _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~, formato normal.
- aqui podemos usar *formatio italico*, pero también **bold** y ~~tachado~~. 

# Listas
1. Esto es un item de lista ordenada. 
2. Esto es un item de lista ordenada. 
3. Esto es un item de lista ordenada. 
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="http://www.google.com"> Eso es un link HTML </a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link en index](index.html)

# Imágenes
![Logo Github](https://cdn.iconscout.com/icon/free/png-256/free-readme-3521667-2945111.png)

# Code Snippets
Código en JSON
```JSON 
{"menu": {  
  "id": "file",  
  "value": "File",  
  "popup": {  
    "menuitem": [  
      {"value": "New", "onclick": "CreateDoc()"},  
      {"value": "Open", "onclick": "OpenDoc()"},  
      {"value": "Save", "onclick": "SaveDoc()"}  
    ]  
  }  
}}
```
Código en Javascript
```Javascript
const num1 = prompt('Enter a first positive integer: ');
const num2 = prompt('Enter a second positive integer: ');

let min = (num1 > num2) ? num1 : num2;

// while loop
while (true) {
    if (min % num1 == 0 && min % num2 == 0) {
        console.log(`The LCM of ${num1} and ${num2} is ${min}`);
        break;
    }
    min++;
}
```
# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi   | Burgos   | 3459358   |
| Tomas  | Thompson | 3438753   |

# Citas
Esto es un texto referente a una cita que pondremos debajo.
> Esto es un cita.

Esto es otro texto que no se relaciona con la cita anterior.
> Esto es otra cita.

# Lineas Divisoras
Esto es un texto que sera dividido guiones medios.

---

Esto es otro texto dividido por asteriscos.

***

Esto es otro texto dividido por guiones bajos.

___

# Saltos de linea
Esto es nuestro primer párrafo.

Esto es nuestro segundo párrafo.

Esto es nuestro tercer párrafo.
- Lista