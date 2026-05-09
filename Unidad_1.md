<p align="center">
  <img src="https://unl.edu.ec/sites/default/files/logogris%20copia.png" width="350">
</p>

<h1 align="center">Universidad Nacional de Loja</h1>
<h3 align="center">Carrera de Computación</h3>
<h4 align="center">Matemáticas Discretas</h4>


---

# Portafolio de Matemática Discreta – ACD1

**Estudiante:** Alison Cristina Ramirez Villavicencio

**Docente:** Ing. Mario Enrique Cueva 

**Asignatura:** Matemáticas Discretas  

**Ciclo:** Primer Ciclo - Computación  

**Fecha:** 7 de mayo de 2026

---

## Objetivo del Portafolio

*Consolidar el aprendizaje de lógica proposicional mediante la elaboración de un portafolio que evidencie comprensión teórica, desarrollo de ejercicios y aplicación práctica.*
---

## 📑 Índice
1. [Resumen Teórico](#1-resumen-teórico)
2. [Ejercicios Resueltos](#2-ejercicios-resueltos)
3. [Ejercicio Aplicado](#3-ejercicio-applied)
4. [Reflexión Personal](#4-reflexión-personal)

---

## 1. 📖 Resumen Teórico

### ● Definición de Proposición
Una proposición es un enunciado declarativo que puede ser calificado como **verdadero (V)** o **falso (F)**, pero no ambos a la vez. Desde una perspectiva computacional, las considero la unidad básica de procesamiento de información lógica.

### ● Tipos de Proposiciones
*   **Simples (Atómicas):** No contienen conectores lógicos. 
    *   *Ejemplo:* "La computadora está encendida".
*   **Compuestas (Moleculares):** Resultan de la unión de dos o más proposiciones mediante conectores.
    *   *Ejemplo:* "La computadora está encendida **y** tiene conexión a internet".

### ● Conectores Lógicos
| Símbolo | Nombre | Lectura | Definición Corta |
|:---:|:---:|:---:|:---|
| ¬ | Negación | No | Invierte el valor original. |
| ∧ | Conjunción | Y | Verdadera solo si ambas son V. |
| ∨ | Disyunción | O | Falsa solo si ambas son F. |
| → | Condicional | Si... entonces | Falsa solo si el antecedente es V y el consecuente F. |
| ↔ | Bicondicional | Si y solo si | Verdadera si ambos valores son iguales. |

### ● Explicación de Tablas de Verdad
Son herramientas que permiten analizar todas las combinaciones posibles de valores de verdad de un argumento. Se clasifican en:
*   **Tautología:** El resultado final es siempre verdadero.
*   **Contradicción:** El resultado final es siempre falso.
*   **Contingencia:** El resultado final alterna entre V y F.

### ● Principales Leyes Lógicas
Permiten la simplificación de expresiones complejas:
*   **Leyes de De Morgan:** $\neg(p \land q) \equiv \neg p \lor \neg q$ y $\neg(p \lor q) \equiv \neg p \land \neg q$.
*   **Doble Negación:** $\neg(\neg p) \equiv p$.
*   **Idempotencia:** $p \land p \equiv p$ ; $p \lor p \equiv p$.
*   **Conmutativa:** $p \land q \equiv q \land p$.

### ● Reglas de Inferencia
Esquemas para deducir conclusiones válidas:
*   **Modus Ponendo Ponens (MPP):** Si $[(p \to q) \land p] \implies q$.
*   **Modus Tollendo Tollens (MTT):** Si $[(p \to q) \land \neg q] \implies \neg p$.
*   **Silogismo Hipotético:** Si $[(p \to q) \land (q \to r)] \implies (p \to r)$.

---
---

### 2. 📊 Ejercicios Resueltos (Mínimo 5)
*Explora el desarrollo paso a paso y las herramientas de verificación para cada categoría.*

> ### *Encuentre todos los ejercicios aquí*
> * [Ejercicios_Resueltos_📊](./Evidencias)

<details>
  <summary><b>🔣 Ejercicio 1: Traducción de lenguaje natural a simbólico</b></summary>

  *   **Descripción:** Conversión de enunciados cotidianos a fórmulas lógicas.
  *   **Resolución:** [📄 Ver resolución en PDF](./Evidencias/ejercicios_A.pdf)
  *   **Evidencia en la nube:** [📂 Google Drive Backup](https://drive.google.com/drive/folders/1YarHL1AHvEaN6RDQ8HCnw1_Pt0CQMoC7_)
  *   **Laboratorio Virtual:** [Simulador de Traducción Lógica](https://web.stanford.edu/class/cs103/tools/truth-table-tool/)
</details>

<details>
  <summary><b>📋 Ejercicio 2: Construcción de tablas de verdad</b></summary>

  *   **Descripción:** Análisis exhaustivo de todas las combinaciones de verdad posibles.
  *   **Resolución:** [📄 Ver resolución en PDF](./Evidencias/ejercicios_B.pdf)
  *   **Evidencia en la nube:** [📂 Google Drive Backup](https://drive.google.com/drive/folders/1YarHL1AHvEaN6RDQ8HCnw1_Pt0CQMoC7_)
  *   **Laboratorio Virtual:** [Generador Automático de Tablas](https://mrieppel.net/prog/truthtable.html)
</details>

<details>
  <summary><b>⚖️ Ejercicio 3: Identificación de tautologías, contradicciones y contingencias</b></summary>

  *   **Descripción:** Clasificación del resultado final de una tabla de verdad.
  *   **Resolución:** [📄 Ver resolución en PDF](./Evidencias/ejercicios_C.pdf)
  *   **Evidencia en la nube:** [📂 Google Drive Backup](https://drive.google.com/drive/folders/1YarHL1AHvEaN6RDQ8HCnw1_Pt0CQMoC7_)
  *   **Laboratorio Virtual:** [Verificador de Clasificación Lógica](https://www.erpelstolz.at/gateway/TruthTable.html)
</details>

<details>
  <summary><b>🛠️ Ejercicio 4: Aplicación de leyes proposicionales</b></summary>

  *   **Descripción:** Simplificación de expresiones mediante reglas lógicas.
  *   **Resolución:** [📄 Ver resolución en PDF](./Evidencias/ejercicios_D.pdf)
  *   **Evidencia en la nube:** [📂 Google Drive Backup](https://drive.google.com/drive/folders/1YarHL1AHvEaN6RDQ8HCnw1_Pt0CQMoC7_)
  *   **Laboratorio Virtual:** [Calculadora de Álgebra Booleana](https://www.boolean-algebra.com/)
</details>

<details>
  <summary><b>✅ Ejercicio 5: Validación de argumentos</b></summary>

  *   **Descripción:** Demostración de la validez de una conclusión a partir de premisas.
  *   **Resolución:** [📄 Ver resolución en PDF](./Evidencias/ejercicios_E.pdf)
  *   **Evidencia en la nube:** [📂 Google Drive Backup](https://drive.google.com/drive/folders/1YarHL1AHvEaN6RDQ8HCnw1_Pt0CQMoC7_)
  *   **Laboratorio Virtual:** [Probador de Validez Lógica](https://www.umsu.de/trees/)
</details>

---

### 3. 🧠 Ejercicio Aplicado (Caso Real)
<details>
  <summary><b>💡 CLIC PARA VER CASO: Acceso al Sistema Académico</b></summary>

  * **Planteamiento:** Se analiza la seguridad de acceso a una plataforma académica:
    ## "Si el usuario ingresa la contraseña correcta o utiliza el reconocimiento facial, entonces se concede el acceso al sistema".
  * **Definición de proposiciones:** 
    * $p$: El usuario ingresa la contraseña correcta.
    * $q$: El usuario utiliza el reconocimiento facial.
    * $r$: Se concede el acceso al sistema.
  * **Expresión simbólica:** $(p \lor q) \to r$.
  * **Conclusión:** El sistema valida la identidad y el acceso se concede satisfactoriamente ($r = V$).
  * **Resolución:** [📄 EJERCICO APLICADO](.Evidencias/EJERCICIO_DE_LÓGICA_PROPOSICIONAL.pdf)
</details>

---

### 🔍 4. Reflexión Personal
<details>
  <summary><b>🤔 CLIC PARA LEER MI APRENDIZAJE</b></summary>

  *   **¿Qué fue lo más difícil de entender?**

      *No considero que existieran realmente adversidades en el momento de comprender los temas expuestos, pero debo recalcar que el uso de las leyes de inferencia representó un pequeño momento de confusión al intentar descubrir qué ley usar en cada caso. Pero luego de ejercer distintas prácticas, se me ha facilitado el uso de las Leyes mencionadas.*
  *   **¿Qué tema comprendí mejor?**

      *Las Tablas De Verdad, es un tema del que ya tenía bases provenienes del colegio, por lo tanto, la aplicación de las mismas fue considerablemente sencillo.*
  *   **¿Cómo puedo aplicar la lógica en mi carrera?**

      *Como estudiante de Computación en la **Universidad Nacional de Loja**, la lógica proposicional es la base para el desarrollo de algoritmos y la resolución de problemas técnicos.*
</details>

## 📂 Anexos: Aprendizaje Práctico Experimental (APE)

A continuación, se presentan los enlaces a las actividades prácticas desarrolladas. Todos los archivos se encuentran alojados en el repositorio de Google Drive de la asignatura:

| Actividad | Recurso | Enlace Directo |
|:---:|:---|:---:|
| **Carpeta General** | Todos los APE (1 al 6) | [📁 Acceder a Drive](https://drive.google.com/drive/folders/1glwZf-NODxVgNpHMM8H6M5cQ_cgqSs8U) |
| **APE 01** | Lógica y Simbolización | [🔗 Ver Documento](https://drive.google.com/drive/folders/1glwZf-NODxVgNpHMM8H6M5cQ_cgqSs8U) |
| **APE 02** | Tablas de Verdad | [🔗 Ver Documento](https://drive.google.com/drive/folders/1glwZf-NODxVgNpHMM8H6M5cQ_cgqSs8U) |
| **APE 03** | Leyes Lógicas | [🔗 Ver Documento](https://drive.google.com/drive/folders/1glwZf-NODxVgNpHMM8H6M5cQ_cgqSs8U) |
| **APE 04** | Circuitos y Compuertas | [🔗 Ver Documento](https://drive.google.com/drive/folders/1glwZf-NODxVgNpHMM8H6M5cQ_cgqSs8U) |
| **APE 05** | Reglas de Inferencia | [🔗 Ver Documento](https://drive.google.com/drive/folders/1glwZf-NODxVgNpHMM8H6M5cQ_cgqSs8U) |
| **APE 06** | Proyecto de Unidad | [🔗 Ver Documento](https://drive.google.com/drive/folders/1glwZf-NODxVgNpHMM8H6M5cQ_cgqSs8U) |

> **Instrucción para el docente:** Al hacer clic en los enlaces, se abrirá la carpeta de Google Drive que contiene las evidencias, ejercicios y capturas de pantalla de cada actividad práctica.
