# semantic-segmentation_Clothing-

CNNs para segmentación semántica
Ahora que tenemos claro en qué consiste la segmentación semántica y la multitud de aplicaciones que tiene, vamos a ver cómo podemos afrontar este problema con CNNs.

Antes de nada, debemos destacar que la segmentación semántica se trata como un problema de aprendizaje supervisado. Esto quiere decir que para aprender los modelos debemos disponer de imágenes con sus segmentaciones ideales.

Para poder mostrar esto e ilustrar el resto del notebook, nos vamos a centrar en un problema concreto basado en el dataset Clothing Co-Parsing (CCP). Este dataset está enfocado a la segmentación semántica de prendas de vestir. Contiene 2,098 imágenes de alta resolución tomas en entornos abiertos, principalmente urbanos. De ellas 1,004 imágenes han sido etiquetadas utilizando 59 etiquetas que abarcan una gran cantidad de prendas de vestir, accesorios, etc.
