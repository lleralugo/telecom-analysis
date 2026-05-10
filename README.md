# telecom-analysis
Análisis exploratorio y segmentación de usuarios de telecomunicaciones usando Python, Pandas y visualización de datos.
# 📊 ConnectaTel - Customer Usage Analysis

## 📌 Objetivo del Proyecto

El objetivo de este proyecto es realizar un análisis exploratorio de datos (EDA) sobre el comportamiento de usuarios de ConnectaTel una empresa de telecomunicaciones.


El análisis busca:

- Detectar problemas de calidad en los datos.
- Analizar patrones de uso de clientes.
- Identificar segmentos de usuarios.
- Detectar valores atípicos (outliers).
- Generar insights accionables para el negocio.

---

# 🗂️ Datasets Utilizados

El proyecto utiliza datasets relacionados con clientes y uso de servicios:

## `users`
Contiene información demográfica de los usuarios:

- `user_id`
- `age`
- `city`
- `plan`
- `reg_date`

## `usage`
Contiene información de actividad de los usuarios:

- `user_id`
- `type`
- `duration`
- `length`

---

# ⚙️ Etapas del Análisis

## 1. Limpieza de Datos
- Tratamiento de valores nulos.
- Reemplazo de valores inconsistentes (`?`, fechas futuras, etc.).
- Conversión de tipos de datos.

## 2. Análisis Exploratorio (EDA)
- Distribuciones de edad.
- Distribuciones de llamadas, mensajes y minutos.
- Histogramas y boxplots.
- Identificación de outliers.

## 3. Ingeniería de Características
Se crearon nuevas variables como:
- `cant_mensajes`
- `cant_llamadas`
- `cant_minutos_llamada`
- `grupo_edad`
- `grupo_uso`

## 4. Segmentación de Usuarios
Segmentación por:
- Edad
- Nivel de uso

## 5. Insights Ejecutivos
Se generaron recomendaciones de negocio basadas en:
- Patrones de consumo
- Usuarios de alto valor
- Comportamientos extremos

---

# 📈 Herramientas Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

# ▶️ Cómo Ejecutar el Proyecto

## Opción 1: Google Colab
1. Descargar el notebook `.ipynb`
2. Abrir Google Colab:
   https://colab.research.google.com/
3. Subir el notebook.
4. Ejecutar las celdas en orden.

## Opción 2: Jupyter Notebook
Instalar dependencias:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Ejecutar:

```bash
jupyter notebook
```

Abrir el archivo `.ipynb` y correr las celdas.

---



---

# 💡 Principales Hallazgos

- La mayoría de usuarios pertenece al segmento de uso medio.
- Los usuarios adultos representan el grupo más grande.
- Existen usuarios de alto consumo que podrían considerarse clientes premium.
- Los outliers detectados representan comportamientos reales y no errores de captura.

---

# 📬 Autor

Proyecto realizado de análisis de datos y visualización usando Python.
