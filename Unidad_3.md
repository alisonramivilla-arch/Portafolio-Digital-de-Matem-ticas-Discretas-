# 🌐 Portafolio Digital de Matemáticas Discretas
# 📚 Unidad 3: Teoría de Grafos y Árboles

<p align="center">
<img src="https://img.shields.io/badge/Unidad-3-blue?style=for-the-badge">
<img src="https://img.shields.io/badge/Asignatura-Matemáticas_Discretas-green?style=for-the-badge">
<img src="https://img.shields.io/badge/Tema-Grafos_y_Árboles-orange?style=for-the-badge">
</p>

---

# 📖 Introducción

La **Teoría de Grafos y Árboles** constituye una de las ramas más importantes de las Matemáticas Discretas y de la Ciencia de la Computación. Su estudio permite representar relaciones entre diferentes elementos mediante estructuras que facilitan la resolución de problemas complejos.

Actualmente estas estructuras son utilizadas en aplicaciones tan diversas como los sistemas GPS, las redes sociales, el funcionamiento de Internet, la inteligencia artificial, la optimización de rutas de transporte, la organización de archivos en un computador y el diseño de redes de comunicación.

Durante esta unidad se desarrollaron actividades teóricas, prácticas y experimentales que permitieron comprender el funcionamiento de los grafos y árboles, así como sus principales algoritmos y aplicaciones en el mundo real.

---

# 🎯 Objetivos de la Unidad

- Comprender la estructura y funcionamiento de los grafos.
- Analizar las diferentes representaciones de un grafo.
- Identificar las características de los árboles.
- Aplicar algoritmos de búsqueda y recorrido.
- Resolver problemas mediante estructuras no lineales.

---

# 📚 Componentes del Portafolio

| Componente | Descripción |
|------------|-------------|
| 👨‍🏫 ACD | Actividades desarrolladas junto al docente. |
| 📖 AA | Investigación y trabajo autónomo. |
| 💻 APE | Desarrollo práctico y experimental. |
| 📝 Evaluación | Evidencias finales de aprendizaje. |

---

# 🌍 ¿Dónde se utilizan los grafos?

```text
           INTERNET
              ●
          /   |   \
         ●    ●    ●
      Router Router Router
```

Los grafos permiten representar conexiones entre diferentes elementos.

### Algunos ejemplos son:

🚗 Google Maps calcula la ruta más corta.

📱 Facebook representa amistades.

✈️ Las aerolíneas optimizan vuelos.

📦 Amazon organiza rutas de entrega.

💻 Internet conecta millones de servidores.

---

> 💡 **Dato curioso**

Google Maps utiliza algoritmos basados en grafos, como **Dijkstra** y **A***, para calcular la mejor ruta entre dos ubicaciones.

---

# 🕸️ Sección 1: Grafos

## ¿Qué es un grafo?

Un **grafo** es una estructura matemática formada por un conjunto de **vértices** (también llamados nodos) y un conjunto de **aristas**, que representan las conexiones existentes entre dichos vértices.

Gracias a esta estructura es posible representar relaciones entre objetos, personas, lugares o sistemas, permitiendo resolver problemas de optimización, comunicación y organización de información.

En informática, los grafos constituyen una herramienta indispensable para el desarrollo de algoritmos eficientes.

---

## Representación de un grafo

```text
        A
      / | \
     B  C  D
      \ | /
        E
```

Cada círculo representa un **vértice**.

Cada línea representa una **arista**.

---

## Tipos de grafos

| Tipo | Características | Ejemplo |
|-------|----------------|----------|
| No dirigido | No existe dirección | Facebook |
| Dirigido | Las conexiones tienen sentido | Twitter |
| Ponderado | Las aristas poseen un peso | Google Maps |
| Completo | Todos los vértices están conectados | Redes pequeñas |
| Bipartito | Dos conjuntos de vértices | Sistemas de asignación |

---

## Aplicaciones de los grafos

✔ Redes sociales

✔ Redes eléctricas

✔ Telecomunicaciones

✔ Inteligencia Artificial

✔ Sistemas GPS

✔ Videojuegos

✔ Redes neuronales

✔ Transporte público

---

### 👨‍🏫 Aprendizaje en Contacto con el Docente (ACD 1)

## Exposición y Defensa de Estructuras de Grafos

Durante esta actividad se estudiaron los diferentes tipos de grafos, sus propiedades fundamentales y las distintas formas de representarlos mediante matrices de adyacencia y listas de adyacencia.

Además, se analizaron ejemplos prácticos relacionados con redes de comunicación y sistemas de transporte.

📄 **Evidencia**

https://drive.google.com/drive/u/0/folders/1ZLzGzlcLQ4E6x6bNMW5t2YYtcaqoly8X

---

### 📖 Aprendizaje Autónomo (AA 1)

## Investigación sobre la Teoría de Grafos

Se desarrolló un informe técnico donde se describen los elementos principales de un grafo, acompañados de ejemplos prácticos que facilitan la comprensión de cada concepto.

Durante esta actividad se fortalecieron habilidades de investigación, análisis y síntesis de información.

📄 **Evidencia**

https://drive.google.com/file/d/1EidkmTrNDkK2SRPo_5rDBV-iA-sb_oSU/view

---

# 🌲 Sección 2: Árboles

Los **árboles** son un tipo especial de grafo que no posee ciclos y mantiene una estructura jerárquica.

Gracias a estas características son ampliamente utilizados para organizar información y acelerar procesos de búsqueda.

---

## Ejemplo de árbol

```text
            A
          /   \
         B     C
        / \   / \
       D   E F   G
```

---

## Aplicaciones de los árboles

🌳 Árboles genealógicos

📂 Sistema de archivos

💻 Compiladores

🤖 Inteligencia Artificial

📊 Bases de datos

🌐 DNS de Internet

---

> 📌 **Importante**

Todo árbol con **n vértices** posee exactamente **n−1 aristas**.

---

## Recorridos de un árbol

| Recorrido | Orden |
|------------|----------------|
| Preorden | Raíz → Izquierda → Derecha |
| Inorden | Izquierda → Raíz → Derecha |
| Postorden | Izquierda → Derecha → Raíz |

---

### 👨‍🏫 Aprendizaje en Contacto con el Docente (ACD 2)

Durante esta actividad se analizaron las propiedades fundamentales de los árboles, los conceptos de raíz, hojas, altura y nivel, además de los principales algoritmos de recorrido.

📄 Evidencia

https://drive.google.com/file/d/1mRbAivNMW-IDSVpiz5bblOYP3lyZJyv3/view?usp=sharing

---

### 📖 Aprendizaje Autónomo (AA 2)

Se realizó un ensayo donde se investigó la importancia de los árboles en informática, incluyendo árboles binarios, árboles AVL, árboles de búsqueda y árboles Huffman.

📄 Evidencia

https://drive.google.com/file/d/1uEzNUvV5LYdAflzzINlNV81xwKQd9eyv/view?usp=sharing
---

# 🚀 Aprendizaje Práctico Experimental (APE)

El **Aprendizaje Práctico Experimental (APE)** permitió aplicar los conocimientos adquiridos durante la unidad mediante el desarrollo de ejercicios y proyectos enfocados en la resolución de problemas utilizando grafos y árboles.

A través de estas actividades se fortalecieron las habilidades de análisis, modelado y aplicación de algoritmos, demostrando la importancia de estas estructuras en la informática y en la solución de situaciones del mundo real.

## 📂 Evidencias del APE

| Actividad | Descripción | Evidencia |
|-----------|-------------|-----------|
| 📌 Fase 1 - 5 | Desarrollo de ejercicios, análisis de grafos, árboles y aplicación de algoritmos. | 🔗 **[Ver documentación del APE](AQUÍ_COLOCA_TU_ENLACE)** |

> 💡 **Competencias desarrolladas**
>
> - Aplicación práctica de grafos y árboles.
> - Resolución de problemas mediante algoritmos.
> - Desarrollo del pensamiento lógico y computacional.
> - Interpretación de estructuras de datos no lineales.

---

# 📝 Evaluación Integradora

La evaluación integradora permitió comprobar el nivel de comprensión alcanzado durante la unidad, reuniendo los conocimientos teóricos y prácticos sobre grafos y árboles. En ella se evaluó la capacidad para analizar problemas, seleccionar la estructura adecuada y aplicar los algoritmos correspondientes.

## 📊 Evidencias de la Evaluación

| Evaluación | Descripción | Evidencia |
|------------|-------------|-----------|
| 📚 Evaluación Integradora | Resolución de ejercicios teóricos y prácticos sobre la Unidad 3. | 🔗 **[Ver evaluación](https://drive.google.com/file/d/1JP_sLpitGf0YkMNNpH018gRqdUhJl0-o/view?usp=sharing)** |

> ⭐ **Resultado esperado**
>
> La evaluación permitió evidenciar el dominio de los conceptos fundamentales de la Teoría de Grafos y Árboles, así como la capacidad para aplicar estas estructuras en la resolución de problemas computacionales.

# 📊 Conclusiones

Durante esta unidad se comprendió que los grafos y árboles constituyen herramientas esenciales para la resolución de problemas en computación.

Su aplicación se extiende desde redes sociales hasta inteligencia artificial, permitiendo representar relaciones, optimizar rutas y organizar información de manera eficiente.

El estudio de estas estructuras fortalece el pensamiento lógico y proporciona las bases para comprender algoritmos avanzados utilizados actualmente en el desarrollo de software.


<strong><a href="Portafolio.md">

