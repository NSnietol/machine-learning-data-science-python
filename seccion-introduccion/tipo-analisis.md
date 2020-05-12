
## Tipos de análisis

* A. predictivo : Agrupa una variedad de técnicas estadísticas de modelización, aprendizaje automático y minería de datos que analiza los datos actuales e históricos reales para hacer predicciones acerca del futuro o acontecimientos no conocido (Wiki).

   * Aprendizaje supervisado, los algoritmos trabajan con datos “etiquetados”, intentado encontrar una función que, dadas las variables de entrada (input data), les asigne la etiqueta de salida adecuada. El algoritmo se entrena con un “histórico” de datos y así “aprende” a asignar la etiqueta de salida adecuada a un nuevo valor, es decir, predice el valor da salida.

        * Árboles de decisión
        * Clasificación de Naïve Bayes 
        * Regresión por mínimos cuadrados
        * Regresión Logística
        * Support Vector Machines (SVM)
        * Métodos “Ensemble” (Conjuntos de clasificadores)

    * Aprendizaje no supervisado tiene lugar cuando no se dispone de datos “etiquetados”  para el entrenamiento. Sólo conocemos los datos de entrada, pero no existen datos de salida que correspondan a un determinado input. Por tanto, sólo podemos describir la estructura de los datos, para intentar encontrar algún tipo de organización que simplifique el análisis. Por ello, tienen un carácter exploratorio.
        * Algoritmos de clustering
        * Análisis de componentes principales
        * Descomposición en valores singulares
        * Análisis de componentes independientes


* A. retroespectivo : Es un enfoque descriptivo que revisa acciones pasadas, con el objetivo de llegar a conclusiones veraces y entender el porqué de algunas situaciones.

### Datos históricos.
Se pueden utilizar para crear el modelo, constantemente se dividirán los datos( Ley de pareto) en :

* Entrenamiento ( 80%)
* Validación (20%)