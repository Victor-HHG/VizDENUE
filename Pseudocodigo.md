# Pseudocódigo

La entrada son los parámetros `scian` y `region`, los cuales serán strings. Se permitirá que `scian` sea entero, pero se transformará en string al comienzo del código

---

`VizDENUE(scian = str, region = str)`
* To String `scian`

* DENUE_SQL(`params`)

    función que se encarga de preparar el texto para la consulta y regresa el conjunto de datos. Se requieren las coordenadas X, Y y el personal ocupado(string)

* Sustitución de la variable `per_ocu` del DENUE por los pesos numéricos correspondientes de un diccionario de valores.
* Estimación de la distribución kernel
* Obtención del mapa (tile)
* Se regresa una imagen

---

La función SCIAN_prep recibe el código SCIAN que introdujo el usuario, ya sea por sector, subsector, rama, subrama o clase, y regresa un conjunto de parámetros necesarios para la consulta en SQL.

---

`SCIAN_prep(scian)`

* Determina el númeno de dígitos solicitados
* ...

---
La función DENUE_SQL se encarga de recibir los parámetros necesarios para la consulta, y regresa el conjunto de datos con las tres variables necesarias para la gráfica.

---

`DENUE_SQL(params)`

* ...

---