# Paint - Programa para Dibujar Figuras con Turtle

Este repositorio contiene un programa interactivo en Python que utiliza la librería **turtle** y el módulo **freegames** para dibujar diferentes figuras geométricas con el mouse y el teclado.  

El usuario puede seleccionar figuras y colores para dibujar libremente sobre la pantalla.  

---

## Contenido del Repositorio 🧩

- **paint.py** → Código principal del programa.  
  Contiene las funciones para dibujar líneas, cuadrados, círculos, rectángulos y triángulos, así como la lógica para manejar los clics del mouse y los atajos de teclado.  

---

## Instrucciones de Uso

1. Ejecuta el archivo `paint.py`.  
2. Haz clic en la ventana para dibujar:  
   - Primer clic: punto de inicio.  
   - Segundo clic: punto final de la figura.  
3. Usa las teclas para seleccionar color o figura:

   | Tecla | Acción                     |
   |:------|:---------------------------|
   | **K** | Color negro            ⚫  |
   | **W** | Color blanco         ⚪    |
   | **G** | Color verde           🟢     |
   | **B** | Color azul               🔵  |
   | **R** | Color rojo           🔴      |
   | **L** | Dibujar línea              |
   | **S** | Dibujar cuadrado           |
   | **C** | Dibujar círculo            |
   | **R** | Dibujar rectángulo         |
   | **T** | Dibujar triángulo          |
   | **U** | Deshacer último trazo      |

---

## Cambios Realizados en el Código 🛠️

Se implementaron las siguientes mejoras en el código original del ejercicio:

1. **Se añadió un color nuevo.**  
   - Se amplió la paleta de colores disponibles para personalizar los dibujos.  

2. **Se completó la función `circle()`.**  
   - Ahora permite dibujar un **círculo** usando los puntos inicial y final como referencia del tamaño.  

3. **Se completó la función `rectangle()`.**  
   - Se agregó la lógica para dibujar un **rectángulo**, calculando la base y altura según la posición del mouse.  

4. **Se completó la función `triangle()`.**  
   - Se programó el dibujo de un **triángulo equilátero** usando los puntos de inicio y fin.  

---

## Descripción General 🎯

Este proyecto forma parte de los ejercicios de programación con **Turtle Graphics**, cuyo propósito es reforzar conceptos de:
- Manipulación de eventos con el mouse y teclado.
- Uso de coordenadas y vectores.
- Construcción de figuras geométricas básicas.  

---

## Autores

**Lizeth Jaqueline Balderas Sánchez**  
**Felipe Gutiérrez Herrera**
---

## Créditos

Basado en el ejercicio “Paint” de la colección **FreeGames** para Python.  
Modificado y extendido con nuevas figuras y colores.

