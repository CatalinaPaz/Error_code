# Aprendiendo Java

## Metadata elements: Information about the page
- < html> especifies using HTNK standard
- < head>  information about the page: title, scripts, CSS
- < title> neisted inside <head> <head> tags
```
<img width="375" height="867" alt="imagen" src="https://github.com/user-attachments/assets/e55f0dbf-8009-49a3-a58e-17b235f3b3af" />
```

Sectioning elements: Define regions
- < p >
- < body>
- < h1> ... < h4>
- < b>
- < em> emphasisi cursiva
- < div>

## Image and Multimedia Tags
- < img src="http..." width="75%"/> especifica la ubicacion en la mism etiqueta por lo que no se necesita etiqueta de cierre. src es obligatoria
- < a href="url de la pagina web"> </a> le haces click y te lleva a otro sitio web.
- Hot-linking, la imagen esta almacenada en otro sitio
```
<a href="https://www.duke.edu/">Duke University</a>
Duke University
```

## Lists and Tables
- Undordenered lists, tag: < ul> < li> ..por cada elemento..< /li> < /ul> todas las vi;etas iguales por defecto
- Ordered list: con numeros  < ol> < li> ..por cada elemento..< /li> < /ol> 
- Podemos hacer lista de imagenes o lista anidada
- Tablas en filas o columnas
-   < table> < /table>
-   Contain rows < tr> < /tr> filas
-   < th> < /th> primera fila, titulos
-   < td> < /td> otras filas


```
<table>
      <tr>
        <th>Food</th>
        <th>Taste</th>
      </tr>
      <tr>
        <td>Apples</td>
        <td>Sweet</td>
      </tr>
      <tr>
        <td>Spinach</td>
        <td>Bitter</td>
      </tr>
```


## CSS para disenar pagina web
Para mejorar la accesibilidad a los usuario, para dar ESTYLO a la pagina web APARIENCIA
- Podemos separar el contenido con el diseno
- Ejempli.... que tamano debe tener la etiqueta < h1>, cual sera su color
- Se usara para escritorio o movil?

Podemos incluir CSS en una pagína web normal incluyendo las etiquetas < style> or < link> para enlazar una hoja de estylos

En este ejemplo cambiamos las propiedades de h1, su alineacion y color. En este caso son todos los elementos de h1
```
HTML
<h1>My favorite food</h1> 
I like a lot of delicious food, some of my favorite are
<ul>
  <li>Chocolate
  <li> Cherries
  <li> Ice cream

CSS
h1 {
  text-align: center;
  color: blue;
}
```

Ahora cambiaremos algunos en específico 
- Aplicando clase HTML < li class="nombre_clase">  CSS .nombre_clase {...}
- Se utilizo por el nombre class=foodLi, ya que es un elememto de la lista que es de comida
- Otra forma es IDs names
- <img width="349" height="169" alt="imagen" src="https://github.com/user-attachments/assets/5f7d0e9b-72f4-463b-a9e0-0fb59ef58512" />

## CSS Colors
- Tenemos 140 nombres de colores (BlueViolet, Gold, FireBick...)
- Podemos identificar un color con su porcentaje de rojo, verde y azul RGB
- rgb( 100, 200, 300)
- Tambien de forma exadesimal #FFD700


## Everything ia a number

- Hardware: bit (0, 1)
- Abstracrion, saber conducir acerlerar con el pedal vs saber el funcionamiento mecanico interno para conducir

### Characteres
- a = 1
### Strings, cadenas
- "Hello"
- 





