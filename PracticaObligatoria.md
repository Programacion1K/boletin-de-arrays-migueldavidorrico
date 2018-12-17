#Práctica obligatoria sobre Arrays

###Normas de entrega
Se exige hacer al menos un commit para cada uno de los apartados.
No se admiten prácticas que no se hayan subido al repositorio de classroom.
No es necesario hacer push para todos los commit pero sí hacer un push al terminar la entrega.
### Enunciado
Se trata de diseñar una clase que permita manejar
direcciones IP cómodamente. Para ello, cada dirección IP
se guardará en un array de 4 ints

## Apartado 1
Se implementará la clase DireccionIP con las siguientes características:
* Debe tener tres constructores: uno al que se le pasa una cadena con la IP
p.e. "192.168.2.3", otro al que se le pasa cuatro enteros separados por comas
p. e. 10,0,03 y otro al que se le pasa un array de cuatro enteros

## Apartado 2
- Se deberá poder obtener la siguiente información de una dirección IP:

    - La clase (A, B, C) a la que pertenece la IP
    - Si es una Id de Red
    - La Id de Red de esa Dirección IP
    - La máscara de red.
    - Si es privada o pública 

- Se deberá disponer de un método infoIP que devuelva la información anterior
debidamente formateada además de un toString que
devuelva la IP escrita normalmente (192.168.1.3)

## Apartado 3
Hacer un método que diga si dos IPs están en la misma red.

Hacer un método que diga si todas las IPs que se le pasan
en un array pertenecen a la misma red.

Hacer un método que devuelva un array con n direcciones IP
todas en la misma red (que se le pasa como argumento). N puede ser muy grande.

## Apartado 4 
Hacer un programa _interactivo_ que muestre el uso de la clase


