# Welcome to Camilo Isaza Web Page

### Software developer from National University of Colombia


## New Repository!
Now you can get the new repository of Visual Computing content.

Link: [acá](https://github.com/caisazafo/VisualComputing)

### Cognitive_ws activity are now available!

## Taller 2 are now available!

## RENDERIZADO DE CAMPOS ESCALARES
![render1](https://scontent.fbog2-1.fna.fbcdn.net/v/t1.0-9/21767947_10156290777374119_6965101709683677132_n.jpg?oh=5c9f9cec5264711a5e4a9302b027cf96&oe=5A56C944)

Existe un algoritmo alternativo desarrollado por Paolo Sabella en 1988; está diseñado con el fin de poder renderizar campos escalares en tres dimensiones. Allí se toman los campos como una densidad variante que emite un nivel básico de dispersión. Este modelo es equivalente a un sistema de particulas que son muy pequeñas.

A lo largo de cada rayo enviado desde el ojo, osea desde el punto de perspectiva, el campo lo podemos ver expresado como una función que tiene el rayo como un parametro.
El algoritmo computa las propiedades del campo a lo largo del rayo y con cada reflexión atenúa su intensidad, densidad máxima y el centro de gravedad.
El campo está mapeado en un espacio de color HSV (Matiz, saturación y valor) que produce una imagen para su visualización.
Las imágenes que se producen de esta manera son percibidas como un espacio de densidad variante donde los realces son atributos computados.
Los principales elementos de este algoritmo son entonces:
1. Renderizado de la sección cruzada
2. umbral de renderizado
Además, se han diseñado estudios en los cuales se ha determinado una equivalencia entre este sistema y otros sistemas discretos de renderizado.

Finalmente, este algoritmo fue medido en un computador SUN4, una imagen de 256x256 px toma 450 segundos en renderizarse; una imagen 512x512 tomaron entre 2550 y 4530 segundos en renderizarse según su complejidad.

![render2](https://scontent.fbog2-1.fna.fbcdn.net/v/t1.0-9/22049893_10156290777414119_7480930627802060121_n.jpg?oh=66d7a45d9e03f1018c2164e8e4562c9f&oe=5A45FA2B)
![render3](https://scontent.fbog2-1.fna.fbcdn.net/v/t1.0-9/22007407_10156290777314119_7578376746703347121_n.jpg?oh=11d0da71f7ffcc984cdea3164491cb8f&oe=5A58FD9B)

	
