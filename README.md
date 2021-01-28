### Universidad Nacional Autónoma de México - Facultad de Ciencias
##### Genómica Computacional
##### Proyecto: Reproducción de una filogenia de la proteína S de diferentes coronavirus.
###### Liliana BS (Lili-K), Adrián CC (itschvzcid), Aldair CR (AldairCoronel), Isaias CG (IsaiasCruz2329), Adrian GP (AdrianGarcia04)

### Introducción
La aparición de la nueva cepa de coronavirus SARS-CoV-2 ha puesto al mundo de rodillas, desde su primer reporte miles de científicos alrededor del mundo del mundo se han dado a la tarea de comprender desde diferentes punto de vista a este nuevo virus. Entre los aspectos más importantes por vislumbrar destacan el conocer su origen ya que es bien sabido que algunas de las actuales enfermedades en humanos guardan un origen zoonótico. Dicho lo anterior, la resolución de este tipo de preguntas pueden encontrar solución llevando a cabo un análisis filogenético.

> La realización de un análisis filogenético consiste en establecer las relaciones de ancestría - descendencia entre diferentes especies empleando para ello secuencias de nucleótidos o aminoácidos de una región en específico o del genoma
completo.  
*(Bioinformatics at COMAV)*
El presente trabajo tiene como objetivo realizar un análisis de carácter filogenético basado en el artículo: **The receptor binding domain of SARS-CoV-2 spike protein is the result of an ancestral recombination between the bat-CoV RaTG13 and the pangolin-CoV MP789. (Flores, et al. 2020).**

Como panorama general es importante mencionar que el SARS-CoV-2 se encuentra dentro del orden *Nidovirales*, familia *Coronaviridae*, subfamilia *Coronavirinae*. Esta última incluye cuatro géneros:
> *alfa -, beta - , gamma - y deltacoronavirus* (α-, β-, γ- y δ-CoV)
*(Hulswit, 2016)*

El agente causante de la enfermedad Covid-19 pertenece a la **subfamilia de los deltacoronavirus *(Pillay, 2010)***. El estudio de las ya mencionadas subfamilias de coronavirus es de gran relevancia ya que estas especies son capaces de infectar a una amplia gama de huéspedes, entre los que se encuentran mamíferos, aves y por supuesto; el ser humano.

Como se mencionó al inicio, la realización de una filogenia puede hacer uso de una región en específico del genoma. Por la relevancia que tiene en el mecanismo de infección para ocasionar la enfermedad Covid-19 se empleará a la denominada **Proteína S (protein spike)** en el presente trabajo. Estructuralmente, la proteína S se divide  en dos subunidades funcionalmente distintas:

> **La subunidad S1:**  involucrada en el reconocimiento del receptor.
> **La subunidad 2:** responsable de la fusión de la envoltura viral y la membrana  de la célula huésped.
(Hulswit, 2016)

En literatura especializada se ha reportado que el genoma del SARS-CoV-2 es 96% idéntico al del coronavirus de murciélago (BatCoV) RaTG13 y 80% idéntico al genoma del SARS-CoV. Mientras que la proteína S de SARS-CoV-2 muestra una identidad de aminoácidos del 93% y 97% con la de BatCoV RaTG13 y Pangolin-CoV respectivamente, lo que ayuda a sustentar con gran certeza el origen de los huéspedes intermediarios de SARS-CoV-2. ***(Pillay, 2020)***

### Objetivo

Reproducir un árbol filogenético de la proteína S de diferentes coronavirus para validar el evento de zoonosis que da origen al SARS-CoV-2.


### Hipótesis

Eventos de zoonosis han sido documentados como agentes causales de pandemias. Dado que SARS-CoV-2 tiene su origen en coronavirus de murciélagos, los resultados deberán mostrar una estrecha relación entre SARS-CoV-2 y distintos coronavirus cuyo huésped son murciélagos.

### Diagrama metodológico

![Diagrama](../meto.jpg)

### Análisis de resultados

El árbol filogenético obtenido a través del programa MrBayes con el modelo evolutivo (GTR-I-G) muestra un parentesco evolutivo entre la proteína S perteneciente a diferentes cepas de virus agrupadas dentro de la familia  *Coronaviridae* que infectan  a murciélagos y al ser humano, lo cual podría reflejar un evento zoonótico.

La falta de conocimiento y experiencia en la elección de los valores para diferentes parámetros usados en el artículo base podría explicar las diferencias en los resultados obtenidos durante la reproducción del árbol filogenético.



### Conclusiones

No fue posible acceder a la gran mayoría del conjunto de datos empleados para la reproducción del árbol filogenético.

El objetivo planteado para el presente trabajo no fue alcanzado debido a que el acceso a las secuencias reportadas en el artículo base fue limitado y además de la metodología enunciada en dicho artículo no se encontraba descrita claramente. Por otro lado, es importante resaltar que descubrimos la gran importancia de contar con recursos de alto poder computacional para poder ejecutar un mayor número de escenarios.


### Literatura consultada:

+ Hulswit, R. J., de Haan, C. A., & Bosch, B. J. (2016). Coronavirus Spike Protein and Tropism Changes. Advances in virus research, 96, 29–57. https://doi.org/10.1016/bs.aivir.2016.08.004
+ Du, L., He, Y., Zhou, Y., Liu, S., Zheng, B. J., & Jiang, S. (2009). The spike protein of SARS-CoV--a target for vaccine and therapeutic development. Nature reviews. Microbiology, 7(3), 226–236. https://doi.org/10.1038/nrmicro2090
+ Pillay, TS. (2020) Gene of the month: the 2019-nCoV/SARS-CoV-2 novel coronavirus spike protein. Journal of Clinical Pathology, 366-369. 10.1136/jclinpath-2020-206658
+ Bioinformatics at COMAV. (s.f) Filogenias. Consultado el 24 de enero de 2021. Recuperado de: https://bioinf.comav.upv.es/courses/intro_bioinf/index.html
+ Flores-Alanis, A., Sandner-Miranda, L., Delgado, G. et al. (2020). The receptor binding domain of SARS-CoV-2 spike protein is the result of an ancestral recombination between the bat-CoV RaTG13 and the pangolin-CoV MP789. BMC Res Notes 13, 398. https://doi.org/10.1186/s13104-020-05242-8
