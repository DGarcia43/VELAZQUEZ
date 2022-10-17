# PRÁCTICA VELAZQUEZ 

## INDICE
1. MAQUETACIÓN
2. IMÁGENES
3. DESCRIPCIÓN
4. LINK A CADA IMAGEN
5. README


Para este proyecto he usado tanto el lenguaje de HTML como CSS.

### MAQUETACIÓN

Lo primero que hemos realizado ha sido una maquetación en la cual 
para marcar los márgenes de la página he usado la etiqueta section 
y a continuación he asignado a cada uno un color para ir ajustando 
todos los márgenes de la página.

### IMÁGENES

Lo siguiente que hice fue colocar todas las imágenes, empecé por las
pequeñas de la izquierda, una vez colocadas las puse en blanco y negro
y cada vez que pases por encima con el ratón saldrá el color original.
```CSS
.imagen{
margin: auto;
display: block;
padding: 20px;
filter: grayscale(100%);
}
.imagen:hover{
filter: grayscale(0%);
transition: 1s;
````
### DESCRIPCIÓN

Lo primero que hemos hecho ha sido elegir el estilo de fuente de google
(nos lo indican en la práctica) y le hemos implementado a través de este 
código en CSS:

```CSS
@import url('https://fonts.googleapis.com/css2? family= Montserrat:wght@200;700 & display=swap');
body{
    font-family:'Montserrat', sans-serif ;
}
```

El siguiente apartado que veremos sera la descripción de cada imagen 
en HTML.

Una vez creada la descripción crearemos el botón de comprar con CSS con
el siguiente código:

```CSS
button{
    background-color:#97c1c0;
    border: none;
    padding: 9px 26px;
    border-radius: 10px;
    font-weight: 700;
}
button:hover{
    background-color: #04c5c0;
}
```
### LINK A CADA IMAGEN

A continuación he usado HTML para hacer referencias a cada una de las 
imagenes que teniamos en el lado izquierdo en pequeño para que al pulsar
encima de ellas salga la imagen en grande con su respectiva descripción.

Para ello hemos usado la etiqueta a href y hemos ido utilizando como 
referencia una página de HTML en la que había una descripción de cada cuadro.

El código que hemos utilizado es el siguiente:

```HTML
<section id="Section1">
    <a href="index.html"><img src="practica01/breda-mini.jpg" alt="Breda" class="imagen"></a>
    <a href="Index2.html"><img src="practica01/venus-mini.jpg" alt="Venus" class="imagen" ></a>
    <a href="Index3.html"><img src="practica01/meninas-mini.jpg" alt="Meninas" class="imagen"></a>
    <a href="Index4.html"><img src="practica01/vulcano-mini.jpg" alt="Vulcano" class="imagen"></a>
    <a href="Index5.html"><img src="practica01/inocencio-mini.jpg" alt="Inocencio" class="imagen"></a>
</section>
```
### README
Por último he realizado este README donde explico todo lo realizado en la práctica.
