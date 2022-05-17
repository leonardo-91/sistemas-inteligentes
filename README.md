## Pontifica Universidad Javeriana
Sistemas-Inteligentes

### Grupo:

*  Edison Leonardo Neira Espitia
* Sergio Rairan
*  Sebastian Herrara

## **Sistema inteligente para la segmentación de clientes con el fin de potencializar y optimizar la conversión de la campaña deposito financiero**

### Contexto

Una institución bancaria portuguesa, propone a través de una campaña de marketing basada en llamadas telefónica, predecir si un usuario se suscribirá a un depósito a plazos. De cada usuario intentan saber atributos como el trabajo actual, el nivel de educación, el incumplimiento financiero, etc. Actualmente, la institución realiza las llamadas sin clasificar ni priorizar clientes, como consecuencia se tiene un tiempo elevado en la labor e incomodidad en clientes que no cumplan con el perfil.

### Objetivo

Aumentar el número de clientes que se suscriben y al mismo tiempo eficientar la operación de la campaña de depósito financiero (CDT) a partir de estrategias orientadas a la conversión de usuarios usando cuatro técnicas de IA utilizando datos de los años 2012 - 2014 con un nivel mínimo de precisión del 80% de conversión, buscando ampliar el recaudo financiero para la compañía (Banco), posibilitando el aumento del índice de inversión y por ende el aumento de las utilidades. Esperamos analizar estos cuatro tipos de técnicas de IA (Redes Neuronales, Algortimos Geneticos, Logica Difusa y Random Forest) por medio de Google Colabs usando Python 3.7 como leguaje de programación, y Scikit-Learn como librería de apoyo para la implementación de los diferentes algoritmos, a su vez usaremos el set de datos públicos de una institución financiera de Portugal que se encuentra alojado en Center of Machine Learning  and Intellignet system (UCI), tenemos como objetivo desarrollar este análisis en el transcurso del curso que se estima será de 3 meses.

### **Desarrollo**

Todo el desarrollo se realizó sobre Google colabs por lo cual en el notebook se podrá ver la respectiva documentación y solución del proyecto aquí expuesto.

### 1. **Resdes Neuronales**

En esta implementacion usamos scikit-learn neuronal network  para entrenar nuestro modelo de prediccion, para mas informacion ver la implementacion en: 

````

[/Proyecto_Final_Sistemas_Inteligentes.ipynb](https://github.com/leonardo-91/sistemas-inteligentes/blob/6e5ac88ee4075be58d11a09742f0772994ddffe5/Proyecto_Final_Sistemas_Inteligentes.ipynb)
````

### 2. **Algoritmo Genetico**

Objectivo PG: Encontrar la mejor combinación de características (Variables)  que mejor  accuracy y sensibilidad generen.

Gen: [0,1] → Significado: 0 -> Descartar Variable  1-> Incluir Variable.

Cantidad Genes: 32

Cromosoma: Array de 32  características.

Cromosoma Inicio:[00000000000000000000000000000001]

Función Fitness: Mejor Accuracy y Sensibilidad (Para evaluar el modelo se tomó la medida accuracy). 

Librería: PyGad [pygad.GA]

Algoritmo Genético:[pygad.gann.GANN] → Algoritmo Red Neuronal

Mas informacion ver la implementacion en: 

````
[/Proyecto_Final_Sistemas_Inteligentes_GA.ipynb](https://github.com/leonardo-91/sistemas-inteligentes/blob/6e5ac88ee4075be58d11a09742f0772994ddffe5/Proyecto_Final_Sistemas_Inteligentes_GA.ipynb)
````

### **Algoritmo Fuzzy**

En esta implementacion usamos la libreria scikit-fuzzy  para entrenar nuestro modelo de logica difusa, nuestras variables fuzzificadas  son: 

* AGE
* MARITAL
* PREVIOUS
* LOAN
* BALANCE
* EDUCATION

Variable Respuesta

* Y

 para mas informacion ver la implementacion en: 

````
[/Proyecto_Final_Sistemas_Inteligentes_Fuzzy_(E7).ipynb](https://github.com/leonardo-91/sistemas-inteligentes/blob/6e5ac88ee4075be58d11a09742f0772994ddffe5/Proyecto_Final_Sistemas_Inteligentes_Fuzzy_(E7).ipynb)
````
*  Nota: En este caso la documentacion y el protocolo experimental se puede encontrar en la carpeta:

````
/Protocolo_Experimental_Fuzzy/
````

### **Random Forest (Aprendizaje Maquina)**

TBD
