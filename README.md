# Argentine Contemporary Art Repository

[English-Spanish]

Museos Abiertos crea en 2021 el 'Repositorio de Arte Contemporáneo Argentino' con su primer dataset proveniente de la 'Colección Bruzzone' la cual contenía, al día 2021/06/07, 2004 registros de objetos (artworks) y 2004 documentos con los datos descriptivos de las obras para 501 WorkAgents (artistas).

Este dataset contiene 

* WorkAgent 501
* Artworks 2004
* Derivatives	images 10997
* Artworks & derivatives 13001
* WorkType Normalized	1283

Este conjunto de datos de investigación contiene 13.001 registros, que representan todas las obras y sus imágenes derivadas y han sido catalogadas en nuestra base de datos. Incluye metadatos normalizados con VRA Core y Dublin Core en Inglés y Español.

| VRA Core                    | Dublin Core                 |
|-----------------------------|-----------------------------|
| VRAE:Admin Cataloguer       | DC:Title                    |
| VRAE:Work Refid             | DC:Creator                  |
| VRAE:Work Agent             | DC:Subject [es]             |
| VRAE:Work Title             | DC:Subject [en]             |
| VRAE:Work Type [es]         | DC:Description [es]         |
| VRAE:Work Type [en]         | DC:Description [en]         |
| VRAE:Work Material [es]     | DC:Publisher                |
| VRAE:Work Material [en]     | DC:Contributor              |
| VRAE:Work Description [es]  | DC:Coverage                 |
| VRAE:Work Description [en]  | DC:Date                     |
| VRAE:Work Measurements      | DC:Type [es]                |
| VRAE:Work Date              | DC:Type [en]                |
| VRAE:Work Location          | DC:Format [es]              |
| VRAE:GPSLatitude            | DC:Format [en] DC:Copyright |
| VRAE:GPSLongitude           | DC:Notice                   |
| VRAE:Image Refid            | DC:Source                   |
| VRAE:Image Relation         | DC:Language                 |
| VRAE:Work Location Creation | DC:Relation                 |
| VRAE:Work Cultural Context  | DC:Identifier               |
| VRAE:Work Style Period      | DC:Identifier               |
| VRAE:Collection Refid       |                             |
| VRAE:Image Rights           |                             |
| VRAE:Image Source           |                             |
| VRAE:Image Href             |                             |

Algunos de estos registros tienen información incompleta y se completarán en próximas versiones.

En este momento, los datos están disponibles en formato CSV, codificados en UTF-8. Aunque UTF-8 es el estándar para las codificaciones de caracteres multilingües, no es interpretado correctamente por Excel en un Mac. Los usuarios de Excel en Mac pueden convertir el UTF-8 a UTF-16 para que el archivo pueda importarse correctamente.


## Additional usage guidelines

### Imágenes no incluídas

Las imágenes no están incluidas y no forman parte del conjunto de datos. Este dataset contiene las URL para visualizar las imágenes que se alojan en nuestro servidor: https://museosabiertos.org/assets/


### Investigación en progreso
Estos datos se facilitan "tal cual" para fines de investigación, su uso queda bajo tu propia responsabilidad. Parte de la información incluida en este conjunto de datos no está completa y no ha sido aprobada por los conservadores. Museos Abiertos ofrece los datos tal y como están y no ofrece representaciones ni garantías de ningún tipo.

Tenemos previsto actualizar periódicamente los conjuntos de datos con información nueva y revisada. Le recomendamos que actualice periódicamente su copia de los conjuntos de datos para asegurarse de que utiliza la mejor información disponible.


### Pull requests
Aceptamos aportes de fuentes comprobadas. Antes de hacer un Pull requests comunícate con nosotros.

### Atribuír a Museos Abiertos
'Museos Abiertos' solicita que se reconozca activamente y se atribuya a 'Museos Abiertos'. Si utilizas uno o ambos conjuntos de datos para una publicación, cítalo utilizando el identificador de objeto digital DOI. La atribución apoya los esfuerzos para liberar más datos y también reduce la cantidad de "datos huérfanos", ayudando a mantener los enlaces a fuentes autorizadas.

### No falsear el conjunto de datos
No engañes a otros ni tergiverses los datos o su fuente. No debes utilizar las marcas comerciales de 'Museos Abiertos' ni afirmar o dar a entender que 'Museos Abiertos' te respalda o a su uso del conjunto de datos.

Siempre que transformes, traduzcas o modifiques de algún modo el conjunto de datos, debes dejar claro que la información resultante ha sido modificada. Si enriqueces o modificas de algún modo el conjunto de datos, considera la posibilidad de publicar el conjunto de datos derivado sin restricciones de reutilización.
