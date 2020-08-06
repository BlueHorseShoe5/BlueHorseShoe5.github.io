---
layout: post
title: "Riesgos coherentes y momentos de orden superior en un portafolio"
permalink: riesgos-coherentes-y-momentos-de-orden-superior-en-un-portafolio
date: 2020-07-12 20:39:11
comments: true
description: "Riesgos-coherentes-y-momentos-de-orden-superior-en-un-portafolio"
keywords: ""
categories:
image: /images/riesgos.jpg
tags:

---

Artzner, Delbaen, Eber y Heath definen el riesgo en términos de cambios en los valores entre dos fechas $$(0,T)$$ argumentan que debido al riesgo, está relacionado con la variabilidad del valor futuro de una posición debido a cambios en el mercado o, en general, a eventos inciertos, es mejor considerar solo los valores futuros. Observaron que no es necesario que los costos iniciales de los componentes de la posición se determinen a partir de precios de mercado universalmente definidos. Una primera medida del riesgo de una posición será si su valor futuro pertenece o no al subconjunto de riesgos aceptables, según lo que decida un organismo regulador como: (a) un regulador que tiene en cuenta lo desfavorable establece cuando se permite una posición de riesgo que puede recurrir a los recursos del gobierno, por ejemplo, como garante de último recurso; (b) una empresa de compensación de una bolsa que tiene que cumplir con las promesas a todas las partes de que las transacciones se completen de manera segura; (c) un administrador de inversiones que sabe que su empresa básicamente ha dado a sus operadores una opción de salida donde el "precio" de ejercicio consiste en ser despedido en caso de grandes pérdidas comerciales en la posición de uno (1998).

## Axiomas de aceptación

Cuando tratamos con el riesgo de mercado, el estado del mundo podría describirse mediante una lista de los precios de todos los valores y todos los tipos de cambio, y suponemos que se conoce el conjunto de todas estas listas posibles. Por supuesto, esto supone que los mercados en la fecha T Son líquidos; si no lo son, se requieren modelos más complicados, donde podemos distinguir los riesgos de una posición y de un patrimonio neto futuro, ya que, con mercados ilíquidos, la asignación de la primera a la segunda puede no ser lineal.
Retomaremos los axiomas más importantes:
* Translation invariance: indica que la función principal de una medida de riesgo es clasificar adecuadamente los riesgos.
* Subaditividad: supongamos que dos escritorios en una empresa calculan de manera descentralizada las medidas ρ (X1) y ρ (X2) de los riesgos que han tomado. Si la función ρ es subaditiva, el supervisor de los dos escritorios puede contar con el hecho de que ρ (X1) + ρ (X2) es una garantía factible en relación con el riesgo global X1 + X2. Si de hecho tiene una cantidad m de efectivo disponible para su negocio conjunto, sabe que imponer límites m1 y m2 con m = m1 + m2, le permite descentralizar su restricción de efectivo en dos restricciones de efectivo, una por escritorio.
* Homogeneidad positiva: Si el tamaño de la posición influye directamente en el riesgo (por ejemplo, si las posiciones son lo suficientemente grandes como para que el tiempo requerido para liquidarlas dependa de sus tamaños), deberíamos considerar las consecuencias de la falta de liquidez al calcular el patrimonio neto futuro de una posición.
* Monotonía: descarta la medida de riesgo definida por ρ (X) = -EP [X] + α · σP (X), donde α> 0 y donde σP denota el operador de desviación estándar, calculado bajo la probabilidad P.

Por lo tanto, la coherencia se define como una medida de riesgo que cumpla con los cuatro axiomas. Por ejemplo: el modelo conocido como “Value At Risk” (VaR) no es una medida de riesgo "coherente", debido al hecho de que el VaR es un cuantil en la distribución de ganancias y pérdidas y no una expectativa y no cumple con el requisito de la subaditividad.


## Activos de riesgo y momentos de orden superior

Los activos riesgosos tienen un importante papel que desempeñar en los portafolios de la mayoría de los inversionistas en un mercado liquido. Los inversionistas suelen ser caracterizados por niveles de riesgo y de riqueza, ciertas estrategias tienden a tener un riesgo similar pero suelen ser diferentes por la naturaleza de los instrumentos; otros tienden a encajar mejor en un grupo de riesgo de tipo patrimonial. La clasificación es arbitraria ya que no hay una definición exacta. Sin embargo, discutiendo el Investment Policy Statement (IPS), puedes encontrar donde pertenece tu cliente con sus respectivas restricciones.

Las mayoría de estrategias de inversión están en función de rendimiento y las expectativas de riesgo - rendimiento por unidad de inversión. En este orden de ideas, los inversionistas son compensados por las distribuciones de rendimientos asociadas con una leptocurtosis y un sesgo negativo, y en algunos casos, sesgo positivo. Como tal, una optimización tradicional de mínima varianza tenderá a no ser preciso, debido a que el mercado no se distribuye de manera normal.

Como lo menciona Brunel (2002) esto crea un enigma, ya que tiende a exponer al inversionista al riesgo de establecer una exposición máxima, buscando soluciones, que van desde un modelo sofisticado hasta un modelo simple. Recordemos que los _hedge funds_ surgieron porque los administradores de portafolios identifican la oportunidad que brinda la liquidez limitada, asimetrías de información y costos de transacción significativos. Implican estrategias que permiten a los inversionistas cambiarse de clases de activos de inversión, sin una restricción por un banco o casa de bolsa. Agentes económicos con estrategias simples que buscan beneficiarse de circunstancias del mercado, o estrategias con características de una distribución de rendimientos normal es insuficiente. Por lo tanto, se debe de buscar medidas que ponderan los pesos para incorporar modelos con una $R^2$ más significativa. Por lo tanto, hay un largo camino por recorrer para poder incorporar los cuatro momentos (promedio, desviación estándar, asimetría y curtosis), correlaciones, co-asimetría y co-curtosis en un portafolio de inversión. Davies, Kat y Lu (2004) identifican que algunos _hedge funds_ incorporan algunos activos debido a una baja co-varianza, un alto co-sesgo y una baja co-curtosis. Finalmente, es interesante incorporar medidas para distribuciones no-Gaussianas en un portafolio.

### Bibliografía

Artzner, Delbaen, Eber y Heath. (1998). Coherent Risk Measures. Mathematical Finance, Vol. 9, No. 3 (July 1999), 203–228.

Brunel, J. (2002). Integrated Wealth Management: The New Direction for Portfolio Managers. Institutional Investor Books.

Davies, Ryan J. and Kat, Harry M. and Lu, Sa, Fund of Hedge Funds Portfolio Selection: A Multiple-Objective Approach (September 2005). Cass Business School Research Paper, ttps://ssrn.com/abstract=476862
