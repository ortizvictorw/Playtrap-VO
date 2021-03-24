# Playstrap-VO
correcciones y estilos personalizados para adaptar en playground DH

____

# Quita Padding


```

 <style 
    type="text/css">
        .lesson__markdown__body {
            padding:30px 0 0 0 !important;
      }
        .lesson__markdown__body p{
           margin-bottom: 5px;
  }
  </style>
 <pre>
  < div class="section">
    CONTENIDO
  </div>  


```
 
 - Remueve el padding que existe entre cada bloque creado , el cual da la sensacion de falta de contenido


_____

# Bloque en edicion

```
<style 
  type="text/css">
      .lesson__markdown__body {
          padding:30px 0 0 0 !important;
    }
      .lesson__markdown__body p{
         margin-bottom: 5px;
}
  </style>

<div class="section" style="
 background: url(https://assets.digitalhouse.com/content/ar/ctd/construcion2.png);
  background-repeat: no-repeat;
  background-size: cover;
height: 550px;

"
>

</div>
<div class="section">
<h1>Proximamente</h1>
<p><span class="bold"> MATERIA:</span> Metodologías de trabajo - TD B1</p>
<p><span class="bold"> UNIDAD:</span> de trabajo y Herramientas</p>
<p><span class="bold"> CLASE:</span> - Lean y Kanban</p>
<p><span class="bold"> TEMA:</span>ón a Lean</p>
</div>
```

img[src*="#thumbnail"] {
   width:150px;
   height:100px;
}
