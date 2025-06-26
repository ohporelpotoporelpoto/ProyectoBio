# Reconstrucción filogenética de gecónidos utilizando 3 genes marcadores
![alt text](https://muchoreptil.wordpress.com/wp-content/uploads/2014/02/1-s2-0-s1055790312000723-gr1.jpg)
## Felipe Soria
## ¿Que organismo o grupo de organismo se utilizara?
* Gekkonidae
## Propósito del proyecto
*El análisis filogenético en la familia Gekkonidae es fundamental para comprender las relaciones evolutivas entre las especies de gecos, un grupo diverso y ampliamente distribuido de reptiles. Este conocimiento es clave para la sistemática, la biogeografía y la conservación de estas especies (Bauer, 2013). Además, la resolución de las relaciones filogenéticas permite clarificar la taxonomía de gekkos, que ha estado históricamente confundida debido a la gran diversidad morfológica y adaptativa del grupo (Vitt & Caldwell, 2013).Los gekkos también son modelos importantes para estudiar adaptaciones evolutivas únicas, como la capacidad para adherirse a superficies verticales gracias a estructuras especializadas en sus patas (Autumn et al., 2002). Entender las relaciones filogenéticas ayuda a contextualizar la evolución de estas adaptaciones y sus bases genéticas (Russell et al., 2015).Finalmente, dado que muchas especies de Gekkonidae habitan en ecosistemas vulnerables o amenazados, un análisis filogenético riguroso es esencial para priorizar esfuerzos de conservación basados en la diversidad genética y filogenética (Frost et al., 2006).

### Objetivo principal

* El objetivo principal es inferir las relaciones evolutivas entre diferentes especies de gekkos (familia Gekkonidae) mediante el análisis de tres genes comunes y altamente informativos (COI mitocondrial, RAG1 nuclear y 12S rRNA), obtenidos mediante NCBI. El proyecto busca mejorar la calidad de los genes, para que la alineación y el arbol filogenético sea mas puro y exacto posible.
* ### Objetivos secundarios
1. Recopilar secuencias de alta calidad de los genes COI, RAG1 y 12S rRNA para distintas especies de gekkos desde la base de datos NCBI.
2. Implementar Conda para gestionar entornos de software y garantizar la instalación y ejecución adecuada de todas las herramientas bioinformáticas necesarias, evitando conflictos entre dependencias.
3. Realizar un control de calidad inicial de las secuencias en formato FASTQ utilizando FastQC, para identificar y eliminar lecturas de baja calidad o contaminadas antes del análisis.
4. Alinear múltiples secuencias de ADN para cada gen (COI, RAG1 y 12S rRNA) usando Muscle, logrando alineaciones precisas que permitan una inferencia filogenética confiable.
5. Seleccionar el mejor modelo evolutivo y construir árboles filogenéticos mediante IQ-TREE, aplicando métodos de máxima verosimilitud y evaluando el soporte estadístico (bootstrap) de las relaciones filogenéticas.
6. Visualizar y editar los árboles filogenéticos obtenidos con FigTree, facilitando la interpretación y presentación clara de las relaciones evolutivas entre las especies de gekkos.
7. Optimizar la calidad de las secuencias y alineaciones a través del flujo de trabajo integrado de estas herramientas, para obtener un árbol filogenético lo más preciso y confiable posible.
8. Interpretar los resultados filogenéticos en el contexto biológico y evolutivo de las especies de gekkos, identificando posibles eventos evolutivos relevantes.
   
## Programas a utilizar
* Conda: Instala y activa un entorno con las herramientas necesarias (FastQC, Muscle, IQ-TREE, FigTree). Esto evita conflictos y facilita reproducibilidad.

* FastQC: Control de calidad de las secuencias. Ejecuta FastQC sobre tus archivos FASTQ para evaluar la calidad de las lecturas. Revisa los reportes para detectar problemas (baja calidad, adaptadores, sesgos).

* Muscle: Alineamiento múltiple. Con las secuencias limpias, realiza alineamientos para cada gen (COI, RAG1, 12S rRNA) por separado. Revisa y edita manualmente las alineaciones si es necesario.

* IQ-TREE: Selección del mejor modelo evolutivo y construcción del árbol. Usa IQ-TREE para elegir el modelo evolutivo adecuado y construir el árbol filogenético basado en máxima verosimilitud.

* FigTree: Visualización y edición del árbol filogenético. Importa el árbol generado en FigTree para visualizarlo, editarlo y preparar figuras para informes o publicaciones.

## Referencias
* Autumn, K., Liang, Y. A., Hsieh, S. T., Zesch, W., Chan, W. P., Kenny, T. W., ... & Full, R. J. (2002). Adhesive force of a single gecko foot-hair. Nature, 405(6787), 681–685. https://doi.org/10.1038/35015073

* Bauer, A. M. (2013). Systematics of the gekkotan lizards (Reptilia: Squamata). Zootaxa, 3721(1), 1–55. https://doi.org/10.11646/zootaxa.3721.1.1

* Frost, D. R., Grant, T., Faivovich, J., Bain, R. H., Haas, A., Haddad, C. F., ... & Wheeler, W. C. (2006). The amphibian tree of life. Bulletin of the American Museum of Natural History, 297, 1–370. https://doi.org/10.1206/0003-0090(2006)297[1:TATOL]2.0.CO;2

* Russell, A. P., Johnson, M. K., & Gaunt, A. S. (2015). The evolution of adhesion in geckos: insights from morphology and biomechanics. Integrative and Comparative Biology, 55(5), 817–831. https://doi.org/10.1093/icb/icv046

* Vitt, L. J., & Caldwell, J. P. (2013). Herpetology: An Introductory Biology of Amphibians and Reptiles (4th ed.). Academic Press.





