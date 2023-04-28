# Modelo_ML_prediccion_pozos_petroleros
La compañía minera OilyGiant busca encontrar el mejor lugar para un nuevo pozo.

Pasos para elegir la ubicación:
* Recolecta los parámetros del pozo de petróleo en la región seleccionada: calidad del petróleo y volumen de reservas;
* Construye un modelo para predecir el volumen de reservas en los nuevos pozos;
* Selecciona los pozos de petróleo con los valores estimados más altos;
* Elige la región con el mayor beneficio total para los pozos de petróleo seleccionados.


Tienes datos sobre muestras de crudo de tres regiones. Ya se conocen los parámetros de cada pozo petrolero de la región. Se srea un modelo que ayude a elegir la región con el mayor margen de beneficio. Analiza los beneficios y riesgos potenciales utilizando la técnica bootstrapping.


## **CONCLUSIÓN GENERAL**

Los datos se encontraban bastante limpios y ordenados, adémas se obtuvo un buen modelo que para 3 casos diferentes consiguió una uniformeidad en sus predicciones con un REMC de entorno al 38% para todos los caso siendo estos valores mas cercanos a 0 en norma general, que es lo que se quere, con lo cual se tiene una predicción más fidedigna de los resultados.

Así mismo el cálculo de los beneficios brutos obtenidos fueron favorables para la región 2, haciendo notar que presenta menos perdidas y mayores ganancias en promedio según el intervalo de confianza, además en el calculo de la probabilidad de perdida del 2.5%, demostró las mismas son un tanto menores para el caso de esta región pudiendo concluir que la sugerencia como mejor elección siendo más rentable para la generación de pozos petoleros sin dudas en la región 2 ya que presenta más ganancias y menos perdidas en promedio además de que el riesgo de perdidas es un tanto menor que el de la región 0 y 1.
