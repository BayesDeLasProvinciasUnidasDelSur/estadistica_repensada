# Orientaciones para la traducción

## 0. Organización del trabajo
Cada capítulo tiene asignada una persona a cargo de la traducción, que es responsable de que esta se lleve a cabo.
La forma de organizarse queda a criterio de cada quien: se puede realizar de forma individual, buscar colaboradores o realizar una actividad abierta de traducción.

## I. Aspectos a tener en cuenta para la traducción del texto

__1. Las traducciones deben intentar encontrar la forma más natural y amplia de decir en español lo que está escrito en inglés.__
En algunos casos eso puede implicar alterar el orden de los elementos de una oración, o agregar palabras que no estaban en el original.
Lo importante es que la traducción "suene" lo más natural posible en español, respetando el sentido que se quiso transmitir en el original.

__2. La variedad dialectal del español que ocuparemos en la traducción es la de Latinoamérica__ (por tamaño de la población).
Trataremos de que sea una versión lo más neutra posible, por lo que:

* Evitaremos expresiones o usos locales/regionales, es decir, que no están extendidos en toda Latinoamérica.
* No utilizaremos el voseo (_vos/vosotros_), usaremos _tu/ustedes_.

__3. Género gramatical.__
A diferencia del inglés, el español tiene género gramatical (masculino, femenino).
En principio, una opción habitual es ajustar la redacción para evitar tener que asignar un género.
Por ejemplo, _for collaborating with other data scientists_ > _para colaborar con otras personas que trabajan en ciencia de datos._

__4. El español es una lengua menos repetitiva que el inglés.__
Como los verbos tienen marca de persona, género y número, tenemos la flexibilidad de poder omitir el sujeto, ya que por contexto se suele entender a qué nos estamos refiriendo.

En todos los casos, hay que tratar de pensar cómo suena más natural/normal en español y cómo queda más claro para quien lee.

__5. Hay regularidades que no siempre se cumplen.__
Por ejemplo, en inglés las palabras con función adjetiva se anteponen a los sustantivos (missing values, help pages, etc.), mientras que en español suele ser al revés: ponemos los adjetivos después del sustantivo (valores faltantes, páginas de ayuda, etc).
Sin embargo, hay casos en que en español la forma "no marcada", es decir, la que nos suena más natural, es con el adjetivo al principio.

En general, ante dudas de este tipo, pensar en qué es lo que suena más natural/normal en español.

__6. El español tiene más modos y tiempos verbales que el inglés__
Al traducir, por lo tanto, se debe priorizar la forma verbal que sea mejor para expresar el sentido del fragmento en español, no la que parezca ser literal del inglés.

__7. Las expresiones idiomáticas no son traducibles de manera literal.__
En caso de que las hubiere (lo iremos descubriendo en el camino), hay que proponer una traducción que permita entender el sentido de ella.

__8. Inconsistencias en el texto original.__
Seguro las iremos encontrando.
La idea es arreglarla en la traducción.

__9. Toma distancia para revisar.__
Cuando trabajamos mucho rato en un texto cuesta identificar errores de tipeo.
Como sugerencia, una vez que termines la traducción del capítulo deja pasar algunas horas (o un día) antes de hacer la última lectura y enviarla.
Eso hace más fácil que salten a la vista este tipo de detalles y permite que quienes hagan la revisión se concentren en la calidad de la traducción más que en correcciones ortotipográficas.

## II. Traducción (o no) de términos técnicos.
Hay términos técnicos que será necesario traducir y otros que no.
El criterio suele estar en si existe una versión en español extendida (o entendible), o si se suele utilizar la versión original en inglés.
En el caso de los últimos, hay que determinar qué género gramatical asignarle y si ofreceremos una traducción explicativa la primera vez que los utilicemos.
A medida que avancemos con la traducción, la idea es ir discutiendo este punto en el canal #dudas-traducción.
A partir de lo que se acuerde, iremos completando las siguientes listas de términos.

#### Términos técnicos que se traducen
Pese a que hay términos que traduciremos al español, es importante que quien traduzca evalúe si corresponde mencionar el término en inglés la primera vez.
En el caso de términos cuya traducción en español no está tan extendida, es necesario evaluar si corresponde agregar una pequeña explicación (por ejemplo, _mapping_ > "..._mapear, es decir, indicar qué variables se asignarán a cada eje_...".

| término en inglés | traducción a utilizar |
| ----------- | ----------- |
| by default | por defecto |
| click | hacer clic |
| console | consola |
| debugging | depurar |
| dataset | conjunto de datos |
| input | entrada |
| intercept | ordenada al origen |
| key | clave |
| legend | leyenda |
| mapping | mapear |
| match | coincidencia |
| missing values | valores faltantes |
| modelling | modelado |
| raw data | datos sin procesar |

#### Términos técnicos que se mantienen
Estos términos irán _en cursiva_.
De ser pertinente, se debe ofrecer una posible traducción al español.

| no traducir    |
| ----------------------------|
| _script_ |


[Las Carpentries](https://github.com/Carpentries-ES/board/blob/master/Convenciones_Traduccion.md) tienen algunas convenciones que podemos ir revisando y ver si se adecuan al propósito de la traducción que estamos realizando.

## III. Traducción del código:

El código no se traduce.
Las distribuciones llevan el nombre en inglés.
