title:: Machine learning at the service of meta-heuristics for solving combinatorial optimization problems: A state-of-the-art

- ## Paper
  background-color:: #49767b
	- ## Metadata
	  Title:: Machine learning at the service of meta-heuristics for solving combinatorial optimization problems: A state-of-the-art
	  Author:: [[Karimi-Mamaghan, Maryam]], [[Mohammadi, Mehrdad]], [[Meyer, Patrick]], [[Karimi-Mamaghan, Amir Mohammad]], [[Talbi, El-Ghazali]]
	  Journal:: [[Eur. J. Oper. Res.]]
	  Language:: [[Inglés]] 
	  Type:: [[Paper]] 
	  Keywords::  [[Machine Learning]], [[Optimization]], [[Metaheuristics]]
	  Year:: 2021 
	  Status::
	  Start::
	  End::
	  Link:: https://paperpile.com/app/p/db99884d-f125-0771-b1ef-826f7f2fd4ad
	- ## Abstract
	- In recent years, there has been a growing research interest in integrating machine learning techniques into meta-heuristics for solving combinatorial optimization problems. This integration aims to lead meta-heuristics toward an efficient, effective, and robust search and improve their performance in terms of solution quality, convergence rate, and robustness. Since various integration methods with different purposes have been developed, there is a need to review the recent advances in using machine learning techniques to improve meta-heuristics. To the best of our knowledge, the literature is deprived of having a comprehensive yet technical review. To fill this gap, this paper provides such a review on the use of machine learning techniques in the design of different elements of meta-heuristics for different purposes including algorithm selection, fitness evaluation, initialization, evolution, parameter setting, and cooperation. First, we describe the key concepts and preliminaries of each of these ways of integration. Then, the recent advances in each way of integration are reviewed and classified based on a proposed unified taxonomy. Finally, we provide a technical discussion on the advantages, limitations, requirements, and challenges of implementing each of these integration ways, followed by promising future research directions.
	- ## Notes
	- ![image.png](../assets/image_1656168946641_0.png) ![](https://hypernotes.zenkit.com/api/v1/lists/2362182/files/yF4VmdzLI)
		- Las ventajas de usar ML junto a MH para resolver problemas combinatorios nos ayuda en tres cuestiones: (1) calidad de solución, (2) ratio de convergencia, (3) solidez (robustness).
		- Sobre las diversas técnicas de integración de ML en MH, se puede clasificar desde otro punto de vista:
			- ![image.png](../assets/image_1656168982869_0.png)
		- Este paper ayuda a integrar técnicas de ML a las siguientes partes de las MHs:
			- Selección de algoritmo (Algorithm selection problem [ASP])
				- Esto es útil cuando los recursos (ya sea tiempo o número de núcleos de un procesador) son limitados.
				- Otro motivo es cuando hay muchas MH que funcionan muy bien para las instancias de un problema.
				- También es útil para no expertos que quieren seleccionar de manera apropiada una MH.
				- Es suma, ASP puede ayudar al proceso de "prueba y error" sobre todo cuando hay muchas MH y poco conocimiento del problema.
				- Los retos de la generación de datos:
					- Si las instancias son grandes puede consumir mucho tiempo.
					- Se debe encontrar o generar una manera de tener las suficientes instancias (instances dissimilatiry) para que los algoritmos puedan discriminar (algorithmic discrimination).
			- Evaluación del fitness
				- Fundamental para guiar el proceso de búsqueda hacia espacios de búsqueda que pueden resultar prometedores.
				- Las técnicas de ML pueden servir para dos propósitos: aproximar el fitness o reducirlo.
					- Aproximación está dentro de la categoría de funcional aproximación y evolutiva aproximación:
						- Funcional: Es usado cuando calcular el fitness es muy costoso. En este modelo se reemplaza la función fitness por una con aproximación que imita el original comportamiento tan cerca como sea posible.
						- Evolutiva: Especialmente diseñados para algoritmos evolutivos (EAs).
			- Inicialización
			- Evolución
				- Hay tres técnicas: (1) las que obtiene retroalimentación desde la información de los operadores durante el proceso de búsqueda para seleccionar el más apropiado; (2) las que proveen un modo de aprendizaje para generar buenas poblaciones (algoritmos evolutivos); (3) las que extraen propiedades de las buenas soluciones para generar nuevas soluciones.
				- Selección del operador
					- ![image.png](../assets/image_1656168994858_0.png) ![](https://hypernotes.zenkit.com/api/v1/lists/2362182/files/r18NvNQyfz)
					- Las técnicas de ML son útiles porque permite asignar créditos a cada operador según su rendimiento histórico.
			- Configuración de parámetros
			- Cooperación
		- Líneas posibles de investigación (conclusión):
			- ![image.png](../assets/image_1656169002385_0.png) ![](https://hypernotes.zenkit.com/api/v1/lists/2362182/files/-5Y7IzXdR)
-