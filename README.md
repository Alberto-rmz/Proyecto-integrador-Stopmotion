# Proyecto-integrador-Stopmotion
proyecto integrador sobre una animacion 2d con stop motion de un tiburon
# Animación Stop Motion en Blender 2D: Giro de Tiburón con Grease Pencil

## Descripción

El presente proyecto documenta la creación de una animación tipo *stop motion* en entorno 2D utilizando la herramienta **Grease Pencil de Blender**. La animación se basa en una secuencia de referencia visual que representa el giro de un tiburón, permitiendo estructurar el movimiento a partir de poses clave.

El objetivo principal es aplicar principios fundamentales de la animación, como la construcción cuadro por cuadro, el uso de fotogramas clave y el control del tiempo (*timing*).

---

## Video de referencia

**Blender 2D | Animación con Grease Pencil Paso a Paso**  
https://www.youtube.com/watch?v=0myBDB1vuq0&t=356s

Este recurso sirve como guía para comprender el flujo de trabajo en animación 2D dentro de Blender, especialmente en el uso de Grease Pencil.

---

## Imagen de referencia

La animación se construye a partir de una secuencia dividida en las siguientes etapas:

- Posición inicial  
- Inicio del giro  
- Curvatura del cuerpo  
- Giro medio  
- Punto máximo del giro  
- Enderezamiento  
- Nueva dirección  

Esta división permite planificar el movimiento de forma clara y progresiva.

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/6be28a14-ad9d-487e-aa1a-23f1250e0402" />


---

## Fundamento teórico

El *stop motion digital en 2D* consiste en simular movimiento mediante la creación de dibujos en diferentes fotogramas. En Blender, esto se realiza con Grease Pencil mediante:

- Dibujos por frame  
- Uso de fotogramas clave (*keyframes*)  
- Control del espaciado entre dibujos (*spacing*)  

A diferencia de la animación interpolada, este enfoque se basa en cambios visibles entre cada dibujo, lo que genera un estilo más artesanal.

---

## Requisitos

- Blender (versión 3.x o superior recomendada)  
- Herramienta Grease Pencil  
- Imagen de referencia  
- Conocimientos básicos de dibujo y uso de Blender  

---

## Metodología

### 1. Preparación del entorno

- Abrir Blender  
- Seleccionar plantilla: **2D Animation**  
- Verificar que el objeto Grease Pencil esté activo  

---

### 2. Importación de referencia

- Menú: `Add → Image → Reference`  
- Colocar la imagen en el fondo  
- Ajustar opacidad y escala  

---

### 3. Configuración de la animación

- FPS: 12 o 24 (dependiendo del estilo deseado)  
- Duración: 120 frames  

---

### 4. Creación de poses clave

Se dibujan las poses principales siguiendo la referencia:

| Frame | Acción |
|------|--------|
| 1    | Posición inicial |
| 20   | Inicio del giro |
| 40   | Curvatura del cuerpo |
| 60   | Giro medio |
| 80   | Punto máximo |
| 100  | Enderezando |
| 120  | Nueva dirección |

En cada uno:

- Dibujar el tiburón en la nueva posición  
- Insertar keyframe automático (Grease Pencil lo hace al dibujar)  

---

### 5. Animación cuadro por cuadro

- Activar modo dibujo (*Draw Mode*)  
- Dibujar entre poses clave para suavizar el movimiento  
- Usar menos dibujos si se busca efecto más tipo stop motion  

---

### 6. Uso de Onion Skinning

- Activar Onion Skinning  
- Permite ver dibujos anteriores y siguientes  
- Facilita la continuidad del movimiento  

---

### 7. Ajustes finales

- Revisar fluidez del movimiento  
- Corregir proporciones y consistencia del dibujo  
- Ajustar tiempos si es necesario  

---

### 8. Renderizado

Configuración recomendada:

- Formato: `FFmpeg Video`  
- Codec: `H.264`  
- Resolución: `1920x1080`  


## Resultados esperados

- Animación 2D coherente con la referencia  
- Movimiento construido mediante dibujos secuenciales  
- Estilo visual tipo stop motion  

---

## Resultados esperados

Animacion de tiburon girando y volviendo a su pose
<img width="646" height="339" alt="image" src="https://github.com/user-attachments/assets/417746b1-a345-46be-bb41-c3866aeffb05" />

## Conclusión

La animación 2D con Grease Pencil en Blender permite aplicar principios clásicos de animación en un entorno digital. El uso de referencias visuales y la construcción por etapas facilitan la comprensión del movimiento, mientras que la técnica cuadro por cuadro permite un mayor control artístico.
