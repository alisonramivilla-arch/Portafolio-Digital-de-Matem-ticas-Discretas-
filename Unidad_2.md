# 🌐 Portafolio Digital de Matemáticas Discretas
# 📚 Unidad 2: Lógica Proposicional y Razonamiento Matemático

<p align="center">

<img src="https://img.shields.io/badge/Unidad-2-blue?style=for-the-badge">

<img src="https://img.shields.io/badge/Matemáticas_Discretas-UNL-green?style=for-the-badge">

<img src="https://img.shields.io/badge/Lógica-Proposicional-orange?style=for-the-badge">

</p>

---

# 📖 Introducción

La **Lógica Proposicional** constituye uno de los pilares fundamentales de las Matemáticas Discretas y de la Ingeniería en Computación. Su estudio permite representar razonamientos mediante proposiciones y operadores lógicos, facilitando el análisis de problemas, la validación de argumentos y el diseño de algoritmos.

En informática, la lógica proposicional es indispensable para el funcionamiento de lenguajes de programación, bases de datos, inteligencia artificial, circuitos digitales y sistemas de control. Gracias a ella es posible tomar decisiones mediante estructuras condicionales, verificar programas y diseñar sistemas capaces de responder correctamente ante diferentes situaciones.

Durante esta unidad se desarrollaron actividades teóricas y prácticas orientadas al estudio de las proposiciones, conectores lógicos, tablas de verdad, reglas de inferencia y equivalencias lógicas, fortaleciendo el razonamiento lógico y la capacidad de resolver problemas computacionales.

---

# 🎯 Objetivos de la Unidad

- Comprender los fundamentos de la lógica proposicional.
- Identificar proposiciones simples y compuestas.
- Construir e interpretar tablas de verdad.
- Aplicar reglas de inferencia y equivalencias lógicas.
- Resolver problemas utilizando razonamiento deductivo.
- Relacionar la lógica matemática con la programación y los circuitos digitales.

---
# 📚 Componentes del Portafolio

| Componente | Descripción |
|------------|-------------|
| 👨‍🏫 ACD | Actividades realizadas con el docente. |
| 💻 APE | Desarrollo práctico de la unidad. |
| 📖 AA | Investigación y trabajo autónomo. |
| 📝 Evaluación | Evidencias finales del aprendizaje. |

---

# 🧠 ¿Qué es la Lógica Proposicional?

La **Lógica Proposicional** es una rama de las matemáticas que estudia las proposiciones y la forma en que pueden combinarse mediante operadores lógicos para construir razonamientos válidos.

Una proposición es un enunciado que únicamente puede tener dos valores de verdad:

✅ Verdadero (V)

❌ Falso (F)

Esta característica permite representar problemas reales de forma matemática y facilita el diseño de algoritmos utilizados en informática.

---

## 📌 Aplicaciones de la Lógica Proposicional

💻 Programación

🤖 Inteligencia Artificial

🔒 Ciberseguridad

⚙️ Automatización

📡 Redes de Computadoras

🧩 Diseño de Circuitos Digitales

📊 Bases de Datos

---

> 💡 **Dato curioso**
>
> Cada vez que un programa ejecuta una sentencia `if`, `else` o `while`, está utilizando principios de la lógica proposicional para tomar decisiones.

---

# 🔗 Operadores Lógicos

Los operadores lógicos permiten combinar proposiciones para formar expresiones más complejas.

| Operador | Símbolo | Significado |
|-----------|---------|-------------|
| Negación | ¬ | Niega una proposición |
| Conjunción | ∧ | "Y" |
| Disyunción | ∨ | "O" |
| Condicional | → | "Si... entonces..." |
| Bicondicional | ↔ | "Si y solo si" |

---

## Ejemplo

Sea:

**p:** "Está lloviendo."

**q:** "Llevo paraguas."

Entonces:

- p ∧ q → Está lloviendo **y** llevo paraguas.
- p ∨ q → Está lloviendo **o** llevo paraguas.
- p → q → Si llueve, entonces llevo paraguas.

---

# 📊 Tabla de Verdad

Las tablas de verdad permiten conocer el resultado lógico de una expresión para todas las posibles combinaciones de sus proposiciones.

| p | q | p ∧ q | p ∨ q | p → q |
|---|---|-------|-------|-------|
| V | V | V | V | V |
| V | F | F | V | F |
| F | V | F | V | V |
| F | F | F | F | V |

---

# 💻 La lógica en programación

La lógica proposicional es utilizada constantemente en los lenguajes de programación.

```c
if(usuario == "Admin" && contraseñaCorrecta){
    printf("Acceso permitido");
}
else{
    printf("Acceso denegado");
}
```

En este ejemplo se utiliza la **conjunción (AND)** para comprobar que ambas condiciones sean verdaderas antes de permitir el acceso.

---
---

# 🧩 Mapas de Karnaugh

Los **Mapas de Karnaugh (K-Map)** son una herramienta gráfica utilizada para simplificar funciones booleanas y expresiones lógicas de manera rápida y organizada. Fueron desarrollados por **Maurice Karnaugh** en 1953 y constituyen uno de los métodos más utilizados en el diseño de circuitos digitales.

Su principal objetivo es reducir la cantidad de operaciones lógicas necesarias para implementar una función, disminuyendo el número de compuertas electrónicas y optimizando el rendimiento de los sistemas digitales.

Los Mapas de Karnaugh se construyen a partir de una tabla de verdad y permiten identificar grupos de valores verdaderos (1) para obtener la expresión lógica más simple posible.

---

## 🎯 ¿Por qué son importantes?

Los Mapas de Karnaugh permiten:

✅ Simplificar funciones booleanas.

✅ Reducir el número de compuertas lógicas.

✅ Optimizar circuitos digitales.

✅ Facilitar el diseño de sistemas electrónicos.

✅ Mejorar el rendimiento del hardware.

---

## 📌 Aplicaciones

💻 Diseño de procesadores.

⚙️ Automatización industrial.

🤖 Robótica.

📡 Sistemas embebidos.

🔌 Diseño de circuitos digitales.

🧠 Inteligencia Artificial.

---

## Ejemplo de un Mapa de Karnaugh (2 variables)

| A \ B | 0 | 1 |
|-------|---|---|
| **0** | 1 | 0 |
| **1** | 1 | 1 |

En este ejemplo se agrupan las celdas adyacentes con valor **1** para obtener una expresión booleana simplificada, reduciendo la complejidad del circuito lógico.

> 💡 **Dato curioso**
>
> Aunque actualmente existen programas que realizan la simplificación automáticamente, los ingenieros siguen aprendiendo los Mapas de Karnaugh porque permiten comprender el funcionamiento interno de los circuitos digitales y del Álgebra de Boole.

---

# 🚀 Aprendizaje Práctico Experimental (APE)

El **Aprendizaje Práctico Experimental (APE)** permitió aplicar los conocimientos adquiridos durante la unidad mediante ejercicios progresivos relacionados con la lógica proposicional, tablas de verdad, reglas de inferencia y simplificación mediante Mapas de Karnaugh.

Cada fase fortaleció las habilidades de razonamiento lógico, análisis y resolución de problemas propios de la Ingeniería en Computación.

## 📂 Evidencias del APE

| Fase | Tema | Evidencia |
|------|------|-----------|
| 🔹 Fase 1_2 | Fundamentos de la lógica proposicional y Tablas de verdad| 🔗 **[Ver evidencia](https://drive.google.com/file/d/1nlDovaSpMI4JCRdwIZvSHnHImcUJg-9t/view?usp=sharing)** |
| 🔹 Fase 3_4 | Reglas de inferencia y Equivalencias lógicas| 🔗 **[Ver evidencia](https://drive.google.com/file/d/1VqMhVTfYxroUG18MFSMqmQiSQW3X0Xma/view?usp=sharing)** |
| 🔹 Fase 5_6 | Mapas de Karnaugh y Integración de conocimientos | 🔗 **[Ver evidencia](https://drive.google.com/file/d/1reO7M569rMH4lSmhN-1D86yKYORrP-8k/view?usp=sharing)** |

---

# 📖 Aprendizaje Autónomo (AA)

El **Aprendizaje Autónomo (AA)** permitió complementar los conocimientos adquiridos en clase mediante actividades de investigación, resolución de ejercicios y análisis de aplicaciones reales de la lógica proposicional y el Álgebra de Boole.

Durante esta etapa se profundizó en temas como las reglas de inferencia, equivalencias lógicas, simplificación mediante Mapas de Karnaugh y su aplicación en el diseño de circuitos digitales.

## 📂 Evidencias del Aprendizaje Autónomo

| Actividad | Descripción | Evidencia |
|-----------|-------------|-----------|
| 📚 Investigación | Desarrollo de actividades, ejercicios y análisis de la Unidad 2. | 🔗 **[Ver documento del AA](https://drive.google.com/drive/folders/1G078b2GFvs4yRw4KnEwPDbMeIZDCgwpG?usp=drive_link)** |

> 💡 **Competencias desarrolladas**
>
> - Pensamiento lógico y matemático.
> - Análisis y resolución de problemas.
> - Simplificación de funciones booleanas.
> - Diseño de circuitos digitales.
> - Aplicación de la lógica en programación y sistemas computacionales.

---
# 👨‍🏫 Aprendizaje en Contacto con el Docente (ACD)

Las actividades desarrolladas junto al docente permitieron comprender los fundamentos de la lógica proposicional mediante ejercicios guiados, resolución de problemas y análisis de situaciones aplicadas a la computación.

Durante las clases se abordaron temas como:

- Identificación de proposiciones.
- Construcción de tablas de verdad.
- Operadores lógicos.
- Reglas de inferencia.
- Equivalencias lógicas.
- Resolución de ejercicios.

📂 **Evidencia**

https://drive.google.com/drive/folders/1HG-geUS3IKayl2nTE_W3afoZLCNlmZ6U?usp=drive_link

---

# 📝 Evaluación Integradora

La evaluación integradora permitió comprobar el dominio de los conocimientos desarrollados durante la unidad, incluyendo la resolución de tablas de verdad, reglas de inferencia, equivalencias lógicas y simplificación mediante Mapas de Karnaugh.

## 📊 Evidencias de la Evaluación

| Evaluación | Descripción | Evidencia |
|------------|-------------|-----------|
| 📚 Evaluación de la Unidad 2 | Resolución de ejercicios teóricos y prácticos de lógica proposicional. | 🔗 **[Ver evaluación](AQUÍ_COLOCA_EL_ENLACE)** |

> ⭐ **Resultado esperado**
>
> Al finalizar esta unidad se fortalecieron las capacidades de razonamiento lógico, análisis matemático y resolución de problemas, competencias fundamentales para el estudio de estructuras de datos, algoritmos, arquitectura de computadores y desarrollo de software.

---

📌 **CONCLUSIÓN**

La lógica proposicional constituye la base para el estudio del Álgebra de Boole, los Mapas de Karnaugh y el diseño de circuitos digitales, temas fundamentales para la Ingeniería en Computación.

---
**<strong><a href="Portafolio.md">***PORTAFOLIO***</a></strong>**
