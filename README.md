# Platzom

Platzom es un idioma inventado para el curso de Fundamentos de JavaScript

## Descripción del idioma

- Si la palabra termina en "ar", se le quitan esas dos letras
- Si la palabra inicia con Z, se le añade "pe" al final.
- Si la palabra traducida tiene 10 o más letas, se debe partir en dos por la mitad y unir con un guión en el medio.
- Por último si la palabra original es un palindromo, ninguna regla anterior cuenta y se devuelve la misma pero intercalanso mayúsculas y minúsculas

## Instalación

```
npm install platzom
```

##Uso

```
import platzom from 'platzom'

platzom("Programar") //Program
platzom("Zorro") //Zorrope
platzom("Zarpar") //Zarppe
platzom("abecedario") //acece-dario
platzom("sometemos") //SoMeTeMoS
```

##Créditos
- Glorimar Ramírez

##Licencia

[MIT](https://opensource.org/licenses/MIT)