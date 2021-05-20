**Equipo 2**
# Flujo Máximo: Algoritmo Ford - Fulkerson 
## Proyecto Final
### Optimización 2 2021

| Integrante | User | Clave única | Presentación |
|---------------|-------|---------|-----|
| Ana | @AnaTorresR | 197705 | Expositora |
| Iván | @IvanSalgadoVel | 197704 | Expositor |
| Dira | @diramtz | 197860 | Responder preguntas |
| León| @lgarayva| 148539 | Hacer preguntas |


**Objetivos:** 

1. Crear el paquete para python [ffmaxflow](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-1-segunda-parte-diramtz) que utiliza el algoritmo Ford - Fulkerson para hallar el flujo máximo en una red.
2. [Robustecer](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-2-primera-parte-diramtz) y [optimizar](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-2-segunda-parte-diramtz) el paquete con compilación a C para mejorar su desempeño y mostrar estas mejoras.
3. Utilizar el paquete para resolver problemas de la vida real como los problemas de eliminaciones en una liga de baseball, transporte máximo y el de flujo máximo con demanda.

**Trabajo escrito:** [Reporte](https://github.com/diramtz/ProyectoFinal_MaxFlow/blob/main/reporte_equipo_2.ipynb)

**Presentación:** [Presentación](https://github.com/diramtz/ProyectoFinal_MaxFlow/blob/main/presentacion)   falta

**Implementación:** [código](https://github.com/diramtz/ProyectoFinal_MaxFlow/tree/main/ffmaxc)     

**Publicación del paquete en PyPI:** [ffmaxflow](https://pypi.org/project/ffmaxflow/) 

Nuestro repositorio lleva el nombre de [ProyectoFinal_MaxFlow](https://github.com/diramtz/ProyectoFinal_MaxFlow)


**Notebooks de apoyo:**

En la carpeta [notebooks](https://github.com/diramtz/ProyectoFinal_MaxFlow/tree/main/notebooks) se encuentra material de apoyo para comprensión del código realizado. En esta carpeta, los notebooks están separados por el tipo de problema que resuelven, contienen contexto del problema así como la correcta utilización de los paquetes `ffmaxflow` y `ffmaxc` para resolverlos y una comparación de sus resultados y sus tiempos de ejecución con la paquetería de `networkx`. Los problemas resueltos son:

+ Eliminación en liga de béisbol: Determinar qué equipos son eliminados en cada momento de la temporada, por ejemplo, cuartos de final, octavos de final, final, etc. [Notebook demo](https://github.com/diramtz/ProyectoFinal_MaxFlow/blob/main/notebooks/baseball_elimination.ipynb)
+ Transporte máximo: Hallar la cantidad máxima de personas que pueden volar de una ciudad a otra. [Notebook demo](https://github.com/diramtz/ProyectoFinal_MaxFlow/blob/main/notebooks/airspace_capacity.ipynb)
+ Flujo máximo con demanda: Indica la cantidad de mercancías que deben enviarse por una carretera en particular para satisfacer las demandas [Notebook demo](https://github.com/diramtz/ProyectoFinal_MaxFlow/blob/main/notebooks/circulation_demand_problem.ipynb)

**Binder**

Antes de correr nuestros ejemplos in la consola de Jupyterlab corre el siguiente comando `pip install -r requirements.txt`
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/diramtz/ProyectoFinal_MaxFlow/HEAD?urlpath=lab)

**Referencias**

+ [Práctica 1 primera parte](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-1-primera-parte-diramtz)
+ [Práctica 1 segunda parte](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-1-segunda-parte-diramtz)
+ [Práctica 2 primera parte](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-2-primera-parte-diramtz)
+ [Práctica 2 segunda parte](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-2-segunda-parte-diramtz)
+ [Documentación de nuestro paquete](https://optimizacion-2-2021-1-gh-classroom.github.io/practica-2-segunda-parte-diramtz/)
+ [Cython Documentation](https://cython.readthedocs.io/en/latest/src/userguide/language_basics.html)
+ [cython-sphinx-example](https://github.com/abingham/cython-sphinx-example)
+ [Max Flow Problem Introduction](https://www.geeksforgeeks.org/max-flow-problem-introduction/)
+ [Documentación de nuestro paquete](https://optimizacion-2-2021-1-gh-classroom.github.io/practica-2-segunda-parte-diramtz/maxflow.html)
+ [Cortadura mínima](https://en.wikipedia.org/wiki/Max-flow_min-cut_theorem)
+ [Aplicaciones flujo máximo](https://en.wikipedia.org/wiki/Maximum_flow_problem#Real_world_applications)
+ [Coindidencia bipartita](https://en.wikipedia.org/wiki/Introduction_to_Algorithms)
+ [Kubernetes' Documentation](https://kubernetes.io/es/docs/concepts/)
+ [How to explain Kubernetes in plain English](https://enterprisersproject.com/article/2017/10/how-explain-kubernetes-plain-english)
+ [Kubeflow: Starter’s Guide](https://www.globaldots.com/resources/blog/kubeflow-concepts-use-cases-and-starters-guide/)
+ [5.3 Compilación a C](https://itam-ds.github.io/analisis-numerico-computo-cientifico/V.optimizacion_de_codigo/5.3/Compilacion_a_C.html#compilacion-aot-y-jit)
