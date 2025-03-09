La sintaxis en html para agregar estilos es la siguiente, esto dentro del head del documento html:
```bash
<Style>
    selector{
        propiedad: valor; /*Esta es una declaración*/
    }
</Style>
```
Ejemplo:
- **h1** es un tipo de etiqueta de html.
- **.link** el punto sirve para ubicar una clase, cambiaremos la etiqueta con "class = link".
- **#show** el # sirve para ubicar un id, cambiaremos la etiqueta con "id = show".
```bash
<Style>
    h1{
        color: grey;
    }
    .link{
        color: grey;
    }
    #show{
        color: grey;
    }
</Style>
```
## Etiquetas
## Propiedades
### color
Se puede usar de las siguientes formas:
- **color: rgb(7 185 48 / 50%);** Se especifica el color y su porcentaje de opacicidad.
- **color: rgb(7, 185, 48);** En escala de Red, Green, Blue.
- **color: hsl();** Matiz, Saturacion y Luminosidad
- **color: #932727;** Valor hexadecimal, se puede usar de 3 digitos donde #09f es #0099ff, Si se usa 8 caracteres trabajamos con transparenciia donde 00 es transparente y ff es a su totalidad.
```bash
color: rgb(7 185 48 / 50%);
color: rgb(7, 185, 48);
color: hsla(60, 11.60%, 71.20%); /*hsl(60, 11.60%, 71.20%, 0.78); con opacicidad*/
color:#932727;
```
### border
- **border: width style color**
```bash
border: 3px solid #09f;
```

## Comentarios
    /*Este es un comentario en el html*/
