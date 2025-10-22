<div style="text-align: justify">

# Proyecto 1 - Juego de preguntas.

<br>

## Etapa 2 - CSS.

Aplicar *hojas de estilo en cascada* (CSS) para mejorar la presentación visual del proyecto **Juego de preguntas**.

> Cada alumno deberá personalizar el diseño se´gun el tema elegido en la etapa1 (por ejemplo, si el tema es `Harry Potter`, usar colores relacionados con la saga).

<br>
<br>

## Requisitos técnicos.

- Crear un archivo llamado `styles.css` y vincularlo en las tres páginas HTML (`bienvenida.html`, `cuestionario.html`, `resultado.html`).
- No se debe usar estilos **inline** (`style="..."`), todo debe estar en el archivo CSS.

- Usar selectores, clases e identificadores correctamente.



<br>
<br>

-----

<br>
<br>

**Ayuda**:


<fieldset>
<legend>

 **Colores y fondos** 

</legend>

- Colocar un color o imagen de fondo relacionado con el tema. Usar una paleta coherente (2 o 3 colores principales como máximo).

**Ejemplo de colores de fondo**:

```CSS
body {
  background-color: #0d0d0d;
  color: white;
}

```

**Ejemplo de imagen de fondo**

```CSS
body{
    background-image: url(ruta);
    background-size: cover;
    background-repeat: no-repeat;
}
```

</fieldset>

<br>
<br>

<fieldset>
<legend>

**Botones**

</legend>

- Personalizar los botones para que sean claros y atractivos. Agregar efectos hover (cuando el usuario pasa el mouse encima).

**Ejemplo**:

```CSS
button {
  background-color: #ffcc00;
  border: none;
  padding: 10px 20px;
  border-radius: 8px;
  font-size: 1em;
  cursor: pointer;
}

button:hover {
  background-color: #ffd633;
}


```

</fieldset>

<br>
<br>

<fieldset>
<legend>

**Preguntas**

</legend>

- Organizar las preguntas dentro de cajas o tarjetas. Usar bordes, sombras o fondos suaves para distinguirlas.

**Ejemplo**:

```CSS
fieldset {
  border: 2px solid #555;
  border-radius: 10px;
  padding: 15px;
  margin-bottom: 20px;
  background-color: rgba(255, 255, 255, 0.05);
}

legend {
  font-weight: bold;
  color: #ffcc00;
}

```

</fieldset>



</div>