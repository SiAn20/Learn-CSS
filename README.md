# `LEARN CSS`

# CSS 🛡️

Es un lenguaje de diseño, estilado y declarativo para describir la presentación de un documento.

- **HTML:** Marcado.
- **CSS:** Diseño
- **JavaScript:** Iteratividad

Sus siglas son Cascading Style Sheets (Hojas de estilo en cascada). Cascada por que se lee, procesa y aplica el código desde arriba hacia abajo

## Origen

CSS (Cascading Style Sheets) fue creado en 1996 por Håkon Wium Lie mientras trabajaba en el W3C. Su propósito era separar la estructura del contenido (HTML) del diseño y la presentación.

## Características

- **Separación de contenido y estilo:** Mejora la mantenibilidad y reutilización del código.
- **Cascada y especificidad:** Determina qué estilos se aplican cuando hay conflictos.
- **Herencia:** Algunos estilos se propagan a los elementos secundarios.
- **Responsive Design:** Usa media queries para adaptar diseños a distintos dispositivos.
- **Compatibilidad:** Funciona en todos los navegadores modernos.
- **Modularidad:** Permite crear componentes reutilizables con clases y variables CSS.

# Crear en un nuevo proyecto

Archivo CSS externo:

Crear un archivo styles.css

Enlazarlo en HTML: `<link rel="stylesheet" href="styles.css">`

CSS en línea:

```bash
<p style="color: blue;">Texto azul</p>
```

CSS dentro del head `<style>` dentro de HTML:

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

# Comparación con otras tecnologias 🔍

| Tecnología            | Propósito               | Ventajas                              | Desventajas                                             |
| --------------------- | ----------------------- | ------------------------------------- | ------------------------------------------------------- |
| **CSS**               | Estilos en la web       | Nativo, liviano, flexible             | Puede volverse difícil de mantener en proyectos grandes |
| **SASS/SCSS**         | Preprocesador CSS       | Variables, mixins, anidación          | Necesita compilación                                    |
| **Tailwind CSS**      | Framework de utilidades | Diseño rápido con clases predefinidas | Clases pueden ensuciar HTML                             |
| **Bootstrap**         | Framework UI            | Componentes listos para usar          | Sobrecarga de estilos innecesarios                      |
| **Styled Components** | CSS en JS (React)       | Scoping automático                    | Depende de JavaScript                                   |

# Recursos ⛑️

**Recomendados**

- Aprender CSS: [Manz.dev](https://lenguajecss.com/css/)
- Curso de Google CSS: [Web.dev](https://web.dev/learn/css?hl=es)
- Referencias actualizadas: [MDN web docs](https://developer.mozilla.org/es/docs/Web/CSS)
- Guia visual de propiedades CSS: [css reference](https://cssreference.io/)
- Análizador de CSS, califica tu CSS: [Project Wallace: CSS Analytics](https://www.projectwallace.com/)
- Generar de maquetado:
  - [Flexbox Labs](https://flexboxlabs.netlify.app/)
  - [CSS Layout Generator](https://layout.bradwoods.io/)
- Juegos de CSS:
  - [Codedex](https://www.codedex.io/css)
  - [CSSBattle](https://cssbattle.dev/)
  - [CSS Diner](https://flukeout.github.io/)
- Projectos:
  - [CodeWithCurious](https://codewithcurious.com/web-developement-projects/)
  - [practical-tutorials](https://github.com/practical-tutorials/project-based-learning?tab=readme-ov-file#html-and-css)

**No recomendados**

- **w3schools** Puede tener información desactualizada y erronea.
