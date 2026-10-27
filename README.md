# Presentaciones de Pensamiento Computacional
### Liceo Bicentenario de Pica · Análisis de datos de una encuesta de opinión

Este repositorio reúne las **cuatro presentaciones finales** de la asignatura de Pensamiento Computacional. Todos los grupos trabajaron con la misma encuesta de opinión: cada uno eligió los temas que quería investigar, formuló sus propias preguntas y las respondió analizando los datos con Python.

Cada presentación es un *notebook*: un documento que combina **texto, código y gráficos interactivos**. Se puede leer el razonamiento del grupo, ver el código con que procesaron los datos y explorar los resultados.

---

## 📺 Cómo ver las presentaciones

**No se necesita instalar nada.** Basta con hacer clic en **▶ Ver presentación**, en la tabla de abajo. Se abrirá en el navegador.

Dentro de cada presentación:

- **Se lee de arriba hacia abajo**, como un documento: título, introducción, preguntas, gráficos, análisis y conclusión.
- **Los bloques con código son Python.** No es necesario entenderlos para seguir la presentación, pero muestran el trabajo de programación de los estudiantes.
- **Los gráficos son interactivos:** al pasar el mouse sobre una barra, un punto o una región del mapa aparece el valor exacto. También se puede hacer zoom y ocultar o mostrar categorías haciendo clic en la leyenda.
- La primera vez, la página puede tardar unos segundos en cargar.

> Si se abre un archivo `.ipynb` directamente desde la lista de archivos de GitHub, el texto se verá, pero **los gráficos no aparecerán**. Por eso conviene usar los enlaces **▶ Ver presentación**.

---

## 🗂️ Las cuatro presentaciones

| # | Presentación | Temas | |
|:-:|---|---|:-:|
| 1 | **Vida, Salud y Educación** | Familia · Salud · Educación | [▶ Ver presentación](https://nbviewer.org/github/jaossandon/presentaciones-pensamiento-computacional/blob/main/Apala_Choque_Cruz_Ona.ipynb) |
| 2 | **Libertad en lo privado, protección en lo público** | Familia · Seguridad · Salud | [▶ Ver presentación](https://nbviewer.org/github/jaossandon/presentaciones-pensamiento-computacional/blob/main/Alvarez_Diaz_Ticona.ipynb) |
| 3 | **Bienestar, Medio Ambiente y Proyecto de Vida** | Medio ambiente · Proyecto de vida · Territorio | [▶ Ver presentación](https://nbviewer.org/github/jaossandon/presentaciones-pensamiento-computacional/blob/main/Cortes_Ireland_Nunez.ipynb) |
| 4 | **Percepción, realidad y paradojas** | Seguridad · Educación · Tecnología | [▶ Ver presentación](https://nbviewer.org/github/jaossandon/presentaciones-pensamiento-computacional/blob/main/Alvarez_Cabezas_Cerda_Mamani_Payauna.ipynb) |

---

### 1 · Vida, Salud y Educación
**Integrantes:** Inti Oña, Jorge Cruz, Daner Apala, Yanoica Choque

El grupo eligió cinco afirmaciones de la encuesta y midió cuánto apoyo tiene cada una:

- ¿Las familias monoparentales deberían tener el mismo reconocimiento social que las tradicionales?
- ¿El rol de proveedor económico del hogar debería dejar de asociarse a un género?
- ¿Son las listas de espera en salud pública un problema grave?
- ¿Debería ser obligatoria la educación sexual integral en los colegios?
- ¿Es de buena calidad la educación pública en Chile?

Cada pregunta se presenta con su explicación, una tabla de frecuencias y un gráfico (barras, torta o línea).

---

### 2 · Libertad en lo privado, protección en lo público
**Integrantes:** Orlando Álvarez, Constanza Díaz, Rocío Ticona Paredes

**Pregunta de investigación:** *¿Qué esperan las personas de su vida familiar y qué le exigen al Estado en seguridad y salud? ¿Cambia esto según la edad, el género y la religión?*

Es la presentación más argumentativa. Construye una tesis paso a paso con **diez gráficos**, y cada uno se explica con la estructura *dato → garantía → respaldo → contraargumento*:

1. Quiénes respondieron la encuesta.
2. Por qué la cantidad de respuestas basta para sacar conclusiones.
3. Nivel de acuerdo por tema.
4. Apoyo a las familias homoparentales según género.
5. El mismo apoyo según la edad (gráfico 3D).
6. Opiniones sobre seguridad: portar armas y penas a reincidentes.
7. Mapa de Chile: opinión sobre portar armas por región.
8. El mismo dato del mapa en barras, con la cantidad de personas por región.
9. Qué opiniones van juntas (correlación).
10. Los límites de la tesis: cómo cambian las respuestas según la religión.

**Conclusión del grupo:** las personas quieren **libertad para decidir cómo formar su familia** y, al mismo tiempo, le **exigen al Estado protección en salud y seguridad**.

---

### 3 · Bienestar, Medio Ambiente y Proyecto de Vida
**Integrantes:** Fernanda Ireland, Darlen Cortés, Franchesca Núñez

El grupo busca las prioridades y preocupaciones de la ciudadanía y las relaciones entre ellas. Usa cuatro análisis:

- **Escala de acuerdo (Likert):** dónde hay consenso y dónde las opiniones están divididas.
- **Matriz de correlación:** qué temas tienden a responderse de forma parecida.
- **Análisis por región:** la percepción de la brecha salarial de género a lo largo del país.
- **Mapa de seguridad:** qué tan segura se siente la gente en cada región.

**Conclusión del grupo:** existe una preocupación casi unánime por el cambio climático, junto con escepticismo hacia las medidas del Estado, y se observa un distanciamiento de las ideas tradicionales de éxito, como casarse y tener hijos.

---

### 4 · Percepción, realidad y paradojas
**Integrantes:** Davidl Misael A., Jhosseph Cabezas B., Ghioser Pallauna C., Lido Mamani S., Sayri Cerda M.

El grupo buscó **contradicciones** en las respuestas:

- **Tecnología:** la relación entre la dependencia declarada de las pantallas y el apoyo a restringirlas a menores.
- **Seguridad:** dos mapas de Chile comparan la gravedad que la gente percibe en la delincuencia con lo que realmente le ha pasado (victimización).
- **Inteligencia artificial:** la confianza en la IA para tomar decisiones frente al temor a que reemplace empleos.
- **Educación:** el apoyo a la gratuidad universitaria y a los colegios mixtos según el nivel educacional.

**Conclusión del grupo:** lo que las personas perciben y lo que viven no siempre coincide, y esas tensiones también aparecen en cómo ven la tecnología y la educación.

---

## 📋 Sobre la encuesta y esta versión

- Encuesta de opinión aplicada mediante Google Forms, con preguntas sobre **familia, seguridad, salud, educación, medio ambiente, tecnología, política y trabajo**, además de datos de caracterización (región, rango etario, género, nivel educacional, entre otros).
- La mayoría de las afirmaciones se responden en una escala de 1 (*totalmente en desacuerdo*) a 5 (*totalmente de acuerdo*).
- **Esta versión está ejecutada con las 152 respuestas finales de la encuesta.** Los estudiantes trabajaron y expusieron con las primeras 150, así que algunas cifras escritas en el texto pueden diferir levemente de las que muestran las tablas y los gráficos.
- Los estudiantes trabajaron en Google Colab. Para esta versión, la única modificación al código fue la carga de archivos: en lugar de pedir subirlos manualmente, cada notebook lee `Encuesta.xlsx` y `regiones_chile.geojson` desde esta misma carpeta. El resto del código y todo el texto son los originales de cada grupo.

---

## 📁 Contenido del repositorio

    presentaciones-pensamiento-computacional/
    ├── README.md                                  ← este archivo
    ├── Apala_Choque_Cruz_Ona.ipynb                ← presentación 1
    ├── Alvarez_Diaz_Ticona.ipynb                  ← presentación 2
    ├── Cortes_Ireland_Nunez.ipynb                 ← presentación 3
    ├── Alvarez_Cabezas_Cerda_Mamani_Payauna.ipynb ← presentación 4
    ├── Encuesta.xlsx                              ← respuestas de la encuesta (152)
    ├── regiones_chile.geojson                     ← límites regionales para los mapas
    └── requirements.txt                           ← librerías de Python necesarias

---

## 🛠️ Herramientas utilizadas

- **Python**: lenguaje de programación
- **pandas**: organización y limpieza de datos
- **Plotly**: gráficos interactivos y mapas
- **SciPy**: cálculo de correlaciones
- **Jupyter Notebook**: formato que une texto, código y resultados

---

## 💻 Para volver a ejecutar el análisis (opcional)

Se necesita Python 3 y Visual Studio Code con las extensiones **Python** y **Jupyter**.

1. Descargar el repositorio: botón verde **Code → Download ZIP**, y descomprimirlo.
2. Abrir la carpeta en Visual Studio Code y, en la terminal, crear un entorno e instalar las librerías:

       python -m venv .venv
       .venv\Scripts\python -m pip install -r requirements.txt ipykernel

3. Abrir un notebook, elegir el kernel **.venv** (arriba a la derecha) y presionar **Run All**.

---

*Asignatura de Pensamiento Computacional · Liceo Bicentenario de Pica · Profesor Jorge Álvarez Ossandón*