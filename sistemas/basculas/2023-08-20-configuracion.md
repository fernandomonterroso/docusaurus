---
slug: Configuracion
title: Configuracion
authors:
  name: Fernando Monterroso
  title: Configuracion de basculas
  url: https://github.com/wgao19
  image_url: https://github.com/wgao19.png
tags: [basculas, docusaurus]
---


## Implementación de la página de cálculo de figuras geométricas


|titulo|  autor|
|--|--|
| Divina comedia | Dante |
El objetivo de esta implementación es crear una página web que permita calcular el área y el perímetro de diferentes figuras geométricas.

### HTML

El código HTML define la estructura de la página. Incluye un título (`<h1>`) que muestra "Calculadora de Figuras Geométricas". Luego, hay un contenedor principal con el id "shape-container" que contiene los elementos necesarios para realizar los cálculos.

-   Selector de Figura: Se utiliza un elemento `<select>` con el id "shape-selector" que permite al usuario seleccionar la figura geométrica de la cual desea calcular el área y el perímetro. Cada opción tiene un valor asociado correspondiente al nombre de la figura.
-   Contenedor de Inputs: Se utiliza un `<div>` con el id "inputs-container" para mostrar los campos de entrada específicos de cada figura geométrica. Estos campos se agregarán dinámicamente según la figura seleccionada.
-   Botón de Calcular: Se utiliza un `<button>` con el id "calculate-button" y el texto "Calcular" para realizar los cálculos.
-   Contenedor de Resultado: Se utiliza un `<div>` con el id "result-container" para mostrar el resultado del cálculo de área y perímetro de la figura seleccionada.
