### AlGUNAS ETIQUETAS

```
<!DOCTYPE svg....>
<svg version="" xmlns="" xmlns:xlink="" xml:space="">

  <defs>
    <style>
    </style>
  </defs>

  <g id="" data-name="" transform="">
    <path id="" data-name="" class="" d="aca va la carne" transform="">
  </g>

</svg>
```

### NOTAS

- Un archivo SVG podría comenzar con una declaración XML y una declaración de DOCTYPE svg. Abajo un ejemplo de ambos:
  
```
<?xml version='1.0' encoding='UTF-8' standalone='no' ?>

<!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">

```

- Luego la etiqueta más importante: svg, esta declara el inicio de un *spacename* dentro del cual, todas las etiquetas tienen un significado determinado. Puede contener diferentes atributos, como `version`, `xmlns`, `xmlns:xlink`, y `xmlns:space`. Un ejemplo: 

```
<svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xml:space="preserve">
```

- Al parecer todos estos atributos son necesarios en la declaración del estándar 1.1 de SvG pero no así en el estándar 2.0 **REVISAR**
- 
