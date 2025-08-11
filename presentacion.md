# 📚 Resumen de Ciencia de Datos con Python

## 🐍 Python: Librerías Clave

### 📊 Pandas
**Uso:** Manipulación y análisis de datos tabulares.

**Atributos comunes:**
- `.dtypes`: Tipo de datos por columna  
- `.shape`: Tamaño (filas, columnas)  
- `.mean()`, `.min()`, `.max()`: Estadísticas  
- `.count()`: Valores no nulos por columna  

**Funciones clave:**
- `.head(n)`, `.tail(n)`: Primeras/últimas filas  
- `.describe()`: Estadísticas resumidas  
- `.info()`: Resumen general del DataFrame  
- `.iloc[]`: Acceso por índice  
- `.to_csv()`, `.to_excel()`: Exportar datos  

**Ejercicios:**
- Filtrar usuarios mayores de 30 de países como Canadá, Alemania y Francia.  
  - [Ver código](https://github.com/Marianete/ejercicios?tab=readme-ov-file#-actividad-3-del-d%C3%ADa)  

---

### 📈 Matplotlib
**Uso:** Visualización básica de datos.

**Componentes:**
- `pyplot`: Módulo principal  
- `figure`, `subplots()`: Crear gráficos  

**Tipos de gráficos:**
- Línea: `plt.plot()`  
- Barras: `plt.bar()`  
- Dispersión: `plt.scatter()`  
- Histograma: `plt.hist()`  

**Personalización:**
- Título y ejes: `plt.title()`, `plt.xlabel()`, `plt.ylabel()`  
- Leyenda: `plt.legend()`  
- Cuadrícula: `plt.grid(True)`  
- Guardar gráfico: `plt.savefig('nombre.png')`  

**Ejemplo:**
- [Gráfico de temperaturas](https://github.com/Marianete/ejercicios/blob/main/matploib1.py)  
- [Ver imagen](https://github.com/Marianete/ejercicios/blob/main/Figure_1.png)  

---

## 🤖 Inteligencia Artificial (IA)

**Definición:** Sistemas que simulan comportamiento inteligente.

**Tipos:**
- **IA Débil:** Tareas específicas (Siri, Alexa)  
- **IA General (AGI):** Inteligencia humana total (teórica)  
- **Superinteligencia (ASI):** Superior al humano (hipotética)  

**Aplicaciones:**
- Diagnóstico médico  
- Vehículos autónomos  
- Traducción automática  

---

## 🧠 Machine Learning (ML)

**Definición:** Algoritmos que aprenden de los datos.

**Tipos:**
- **Supervisado:** Datos con etiquetas (ej. detección de spam)  
- **No Supervisado:** Datos sin etiquetas (segmentación)  
- **Reforzamiento:** Aprende por recompensas (ej. AlphaGo)  
- **Deep Learning:** Redes neuronales profundas (ej. reconocimiento facial)  

**Aplicaciones:**
- Recomendaciones personalizadas  
- Predicción de enfermedades  
- Mantenimiento predictivo  

---

## 📂 DataFrame vs Dataset

### 🧾 DataFrame
- Estructura tabular (filas y columnas)
- Usado en Pandas o R
- Tipos de datos variados por columna
- Ideal para análisis estadístico

### 📦 Dataset
- Conjunto de datos (pueden ser tablas, texto, imágenes)
- No siempre tiene estructura fija
- Usado como entrada para modelos de IA/ML

---

## 💽 Big Data: Las 5 V's

1. **Volumen:** Grandes cantidades de datos (TB, PB)  
2. **Velocidad:** Datos en tiempo real (ej. Twitter, NYSE)  
3. **Variedad:** Datos estructurados y no estructurados  
4. **Veracidad:** Calidad y fiabilidad de los datos  
5. **Valor:** Beneficio obtenido del análisis de datos  

**Aplicaciones:**
- Salud: Diagnóstico predictivo  
- Retail: Recomendaciones en tiempo real  
- Transporte: Vehículos autónomos  

**Herramientas comunes:**
- Almacenamiento: Hadoop, Amazon S3  
- Procesamiento: Spark, Flink  
- Limpieza: Pandas, OpenRefine  

---

## 📉 Seaborn

**Uso:** Visualizaciones estadísticas avanzadas y atractivas.

**Gráficos disponibles:**
- Dispersión: `sns.scatterplot()`  
- Histograma: `sns.histplot()`  
- Caja: `sns.boxplot()`  
- Barras: `sns.barplot()`  
- Violín: `sns.violinplot()`  

**Personalización:**
- Títulos y ejes con `matplotlib`:  
  `plt.title()`, `plt.xlabel()`, `plt.ylabel()`  

**Ejemplo práctico:**
- [Ver ejemplo con Seaborn](https://github.com/Marianete/ejercicios/blob/main/seaborn1.py)

---

✍️ **Autor/a:** [Tu Nombre o Usuario]  
📁 Repositorio: [Nombre del Repositorio]

