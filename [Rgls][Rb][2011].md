
<!--```python
import pypdf

def extract_pdf_text(file_path):
    with open(file_path, 'rb') as file:
        reader = pypdf.PdfReader(file)
        text = ""
        for page in reader.pages:
            text += page.extract_text()
    return text

pdf_text = extract_pdf_text('uploaded:Buitres PeñaRueba 2011.pdf')
print(pdf_text[:2000]) # Print first 2000 chars to get an idea of the content

```

```text
Traceback (most recent call last):
  File "<string>", line 11, in <module>
  File "<string>", line 4, in extract_pdf_text
FileNotFoundError: [Errno 2] No such file or directory: 'uploaded:Buitres PeñaRueba 2011.pdf'

```

```python
import pypdf

def extract_pdf_text(file_path):
    with open(file_path, 'rb') as file:
        reader = pypdf.PdfReader(file)
        text = ""
        for page in reader.pages:
            text += page.extract_text()
    return text

try:
    pdf_text = extract_pdf_text('Buitres PeñaRueba 2011.pdf')
    print(pdf_text[:5000])
except Exception as e:
    print(f"Error: {e}")

```

```text-->

# [Rgls][Rb][2011]
*SEGUIMIENTO DE LA REPRODUCCIÓN DE LA  COLONIA DE BUITRE LEONADO (Gyps fulvus) DE PEÑA RUEBA, MURILLO DE GÁLLEGO (ZARAGOZA). Año 2011*
``Propuesta: RB-14014

Dirección Técnica:
Dirección General de Desarrollo Sostenible y Biodiversidad
DEPARTAMENTO DE MEDIO AMBIENTE
Manuel Alcántara de La Fuente
Jefe de Servicio de Biodiversidad

David Guzmán Otano
Jefe de Sección de Especies Catalogadas

Elaboración del estudio:
Departamento de Conservación y Gestión de Especies y Hábitats
Trabajo de campo:
José Luis Rivas

Tratamiento de datos y elaboración de memoria: José Luis Rivas Revisión: Francisco Javier Sampietro SODEMASA-Gobierno de Aragón

<!--INDICE

1. Introducción y objetivos………………….…………………………………… 1
2. Metodología……………………………………………………………………. 1
3. Resultados……………………………………………………………………… 2
4. Discusión……………………………………………………………………….. 3
5. Resultados obtenidos respecto a alimoche………………………………… 9
6. Otras especies rupícolas de interés………………………………………… 9
7. Bibliografía…………………………………………………………………….. 12-->


_________Introducción y objetivos

Durante la temporada de reproducción del presente año, y enmarcado en los trabajos
de localización de ejemplares reproductores de B uitre leonado ( Gyps fulvus) dotados
de marcas alares de lectura a distancia pertenecientes al programa de captura y
marcaje puesto en marcha por la Dirección General  de Biodiversidad, se ha realizado
el seguimiento de la colonia de buitre leonado  localizada en Peña Rueba/Rua ba
(Murillo del Gállego, Zaragoza ) con la finalidad de conocer su éxito reproductor y
valorar sus resultados en relación con la existencia de las diferentes vías de escalada
que se ubican en este enclave.  

Asimismo, e incluido en el trabajo de campo dedicado a las prospecciones de buitre,
se ha prestado especial interés a la presencia de Alimoche ( Neophron percnopterus),
al objeto de localizar el número máximo de parejas nidificantes en el paraje.

Metodología 

Considerando las limitaciones  relacionadas con e l número de jornadas disponibles
para la realización del trabajo de campo y d e acuerdo con las indicaciones recibidas
por parte de la Dirección General de Biodiversidad, se han realizado un total de tres
visitas a la colonia  a lo largo de  la estación reproductora , al objeto de detectar el
máximo número de parejas que ini cian la reproducción (1ª y 2ª  visita), el número de
parejas que fra casan durante la fase de incubación y crianza de los pollos (2ª y 3ª
visita) y el número de parejas que finalizan la reproducción con éxito (3ª visita).

El ámbito del censo se ha circunscrito al macizo de conglomerado cono cido
localmente como Peña Rueba o Ruaba.

Las observaciones se han realizado con prismáticos y telescopio terrestre, a distancias
suficientes para no interfer ir en el comportamiento habitual de las aves , desde varios
puntos de observación para  cada una de las cuatro caras que presenta el enclave, al
objeto de reducir al mínimo el número de parejas reproductoras no localizadas.

El horario seguido ha abarcado toda la jornada solar, concentrando un mayor esfuerzo
durante las primeras y últimas horas del dí a en las que las condiciones  óptimas de la
luz facilitan las tareas de localización y censo.

Los nidos localizados fueron  individualizados y señala dos en  diversos croquis ,
recogiéndose en ellos  las diferentes perspectivas obtenidas desde los diferentes  
puntos de observación utilizados. Por último, toda esta información ha sido reflejada
en panorámicas fotográficas (ver Fig. 2, 3, 4 y 5 ), una por  cada una de las caras de
Peña Rueba.

 Seguimiento de la reproducción de la colonia de buitre leonado  
de Peña Rueba (Murillo de Gállego). Año 2011.
SODEMASA-Gobierno de Aragón  2

               Resultados 

Se realizaron tres visitas correspondientes a los días 17 de febrero, 25 de abril y 13 de junio, localizándose un total de 55 nidos  de buitre leonado , de los que fue posible conocer su éxito reproductor en 49 de ellos.

Su distribución por caras , así como los resultados de la reproducción obtenidos  se
muestra en la Tabla 1.

Tabla.1. Censo y resultados de la reproducción, Peña Rueba 2011.
  N S E W Total
Desconocido 0 1 4 1 6
Fracaso 1 9 6 4 20
Éxito 8 1 19 1 29
TOTAL 9 11 29 6 55

La distribución del número de par

```

```python
# Extract the discussion section and results more fully
print(pdf_text[5000:10000])


```

```text
ejas que inician la reproducción  no se reparte 
equitativamente por las cuatro vertientes, destacando por su importancia la cara Este, 
donde se concentra más de la mitad de la población controlada (52,7%). Le sigue en 
importancia la cara Sur con el 20%, la Norte con 16,3% por último la Oeste con 10,9%. 
 
El éxito reproductor obtenido para el conju nto de la colonia ha sido del 0, 59, algo por 
debajo del 0,72 alcanzado en esta misma temporada para el conjunto de las colonias 
prospectadas en Aragón  (datos propios) , idéntico a l obtenido para todo Aragón 
durante el IV Censo Nacional  de 2008. Comparado con los resultados de este mismo 
censo obtenidos por provincias resulta levemente superior al 0, 50 obtenido en  la 
provincia de Huesca  y prácticamente idéntico al 0,57 obtenido en la provincia de 
Zaragoza (Hernández 2009). 
 
Sin embargo, el porcentaje de fracaso obtenido alcanza el 40,82%, un porcentaje muy 
superior a la med ia obtenida en Aragón en esta misma temporada , con el 27, 57% 
(datos propios). 
 
El mismo análisis realizado por vertientes arroja resultados  más llamativos (Tabla 2) 
con porcentajes muy elevados de fracasos para las caras S y W (del 80% y 90% 
respectivamente) y más moderados en las vertientes Norte y Este. Estas notables 
variaciones coinciden con las diferentes condiciones climatológicas naturales que 
muestran las vertientes más calurosas y soleadas (S y W) y las más frescas (N y E) , 
auque posiblemente también pueda estar distorsionada debido al pequeño tamaño de 
la muestra con la que se han calculado.  
 
Aunque se ha intentado establecer correlaciones significativas entre el fracaso 
reproductor y el numero de vías de escalada por cara, el reducido tamaño de la 
muestra utilizada no ha permitido realizar este cálculo de forma fiable y se ha 
desestimado. 
 
 
 
 
 Seguimiento de la reproducción de la colonia de buitre leonado  
de Peña Rueba (Murillo de Gállego). Año 2011. 
SODEMASA-Gobierno de Aragón  3 
 
 
Tabla.2. Parámetros reproductores obtenidos en Peña Rueba y nº de vías escalada. 
  N S E W Total 
Éxito 
reproductor 0,88 0,1 0.76 0.2 0.59 
Fracaso 
reproductor 11,1% 90% 24% 80% 40,82% 
 
Nº de vías 0 19 9 1 29 
 
 
                    Discusión 
 
Los resultados obtenidos en el presente trabajo deben de considerarse parciales, ya 
que el  número de visitas para llegar a conocer muy ajustadamente el número de 
parejas y el resto de parámetros reproductores debería aumentar a 8 -10, realizándose 
una cada 15 días desde enero hasta abril o mayo incluidos (Del Moral, 2009). 
 
Teniendo en cuenta, a la vista del reducido número de jornadas invertidas, que la cifra 
de parejas censadas debe considerarse como la mínima, parece evidente la reducción 
significativa sufrida por la colonia desde el censo de 2008, cuando fueron censadas en 
este mismo enclave 121 parejas, y que llev ó a incluirla entre las 8 únicas colonias 
consideradas en Aragón como “muy grandes” en función del tamaño de la agrupación 
de las parejas (más de 90 parejas).  Otro dato reseñable, aunque parcial, resulta del 
censo obtenido para la pa red Sur en el censo de 1999, cuando fueron censadas en 
esta pared un total de  26 parejas nidificantes (Fig.1), lo que supondría respecto a las 
11 censadas en 2011 una reducción del 57,7%. 
 
Resulta muy complicado establecer objetivamente algún tipo de re lación entre la 
práctica de la escalada y los diferentes porcentajes de fracaso reproductor obtenidos. 
Las mayores concentraciones de vías de escalada se dan en las vertientes Sur con 19 
vías y una vía ferrata, denominada “ Sur” (Fig. 6 y 8) y Este con 8 vías (Fig. 7 y 9 ). En 
la vertiente Oeste se localiza una única vía ferrata (la “Varella Portillo”) (Fig. 6). 
 
Llama la atención la coincidencia del alto porcentaje de fracasos contrastado en la 
cara Sur con el elevado número de vías presente en esta vertient e, por lo que pudiera 
tratarse de uno  de los factores implicados . A este respecto, convendría disponer de 
datos acerca de la frecuentación  de escaladores por vertientes y/o  vías que 
permitieran clarificar en mayor medida este aspecto. La diferencia con los resultados 
obtenidos en la cara Este, con un número significativo de vías y un porcentaje de 
fracasos mucho más reducido , debe interpretarse considerando la importante 
extensión de esta vertiente y la localización de las vías en un sector determinado de l a 
pared, algo que no ocurre en la vertiente sur donde l as vías se reparten de forma 
mucho más homogénea. 
 
Por otra parte, las importantes diferencias de fracasos obtenidos entre las cara s Norte 
(11,1%) y Este (80%) donde prácticamente no existen vías (sólo  una en la Este) 
cuestionan el supuesto anterior y parecen delatar otros factores no conocidos no 
relacionados con la práctica de la escalada. Seguimiento de la reproducción de la colonia de buitre leonado  
de Peña Rueba (Murillo de Gállego). Año 2011. 
SODEMASA-Gobierno de Aragón  4 
Fig. 1. Croquis con los res


```

Tras el análisis del documento **"Buitres PeñaRueba 2011.pdf"**, se pueden establecer los siguientes patrones de nidificación y reproducción de la colonia de buitre leonado (*Gyps fulvus*) en Peña Rueba según la orientación de las paredes:

### Patrones de Nidificación por Orientación

La distribución de los 55 nidos localizados no es equitativa, mostrando una clara preferencia por determinadas vertientes:

* **Orientación Este (E):** Es la más importante, concentrando el **52,7%** de la población (29 nidos). Presenta un éxito reproductor alto (**0,76**).
* **Orientación Sur (S):** Alberga el **20%** de los nidos (11 nidos). Sin embargo, su éxito reproductor es extremadamente bajo (**0,1**), con un fracaso del **90%**.
* **Orientación Norte (N):** Concentra el **16,3%** de la población (9 nidos). Es la vertiente con mayor éxito reproductor relativo (**0,88**).
* **Orientación Oeste (W):** Es la menos poblada con el **10,9%** (6 nidos). Presenta un éxito bajo (**0,2**) y un fracaso del **80%**.

### Análisis de Factores e Indicios

El estudio discute dos factores principales que podrían influir en estos patrones:

1. **Climatología:** Las vertientes Sur y Oeste son las más calurosas y soleadas, lo que podría estar relacionado con los altos índices de fracaso. Las caras Norte y Este, más frescas, muestran mejores resultados reproductivos.
2. **Actividad Humana (Escalada):** Existe una coincidencia entre el alto fracaso en la cara Sur y el elevado número de vías de escalada (19 vías y una vía ferrata). No obstante, en la cara Este también hay un número significativo de vías (9) pero el éxito es mucho mayor, lo que sugiere que la ubicación puntual de las vías en sectores específicos de la pared Este minimiza las molestias.

### Valores Estadísticos y Robustez

Respecto a la posibilidad de establecer valores estadísticos robustos, el propio documento indica lo siguiente:

* **Muestra limitada:** Se reconoce que el tamaño de la muestra es reducido (55 nidos en un solo año) y que el número de visitas realizadas (3) es insuficiente para obtener parámetros ajustados al 100% (se recomiendan de 8 a 10 visitas).
* **Correlaciones desestimadas:** El informe afirma explícitamente que se intentó establecer una correlación significativa entre el fracaso reproductor y el número de vías de escalada, pero **se desestimó por no ser fiable debido al reducido tamaño de la muestra**.
* **Sesgo potencial:** Se advierte que los porcentajes calculados por vertiente podrían estar distorsionados por la escasez de datos en algunas de ellas.

En conclusión, aunque existen patrones visuales muy marcados (éxito en N/E frente a fracaso en S/W), el estudio **no considera que existan valores estadísticos lo suficientemente robustos** para establecer causalidades definitivas en ese periodo específico.
