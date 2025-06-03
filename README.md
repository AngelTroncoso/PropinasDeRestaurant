# 🍽️ Análisis de Propinas en Restaurantes

> Un estudio exploratorio para entender qué factores influyen en las propinas y cómo optimizarlas.

![Análisis de Propinas](https://scontent.fscl4-1.fna.fbcdn.net/o1/v/t0/f2/m340/AQOaCjpPJfgtOlJLC3H4iM_ix5wq1c3kJfHMtiSUfp5aD_er91P6eZ54GaX1lIuUSYEtdIaqvzNgSqDMo-1V2O6H-I5A1dANOpI0Bs37GT4NQJmPIZd1vOE9DxtBER6N2-f7-D0lEiTxi6XzEyKQTRb8CSjCuQ.jpeg?stp=s1440x1440&_nc_ht=scontent.fscl4-1.fna.fbcdn.net&_nc_gid=6KsIlbUhk-wAUIkVyKhhJw&_nc_cat=109&_nc_oc=AdlLvl5VrjYVhjJ7UOlaOvNIdJj2AxOXU7PKnjU4205ZsOd5deIxl_qLRcEWUoWGdM0&ccb=9-4&oh=00_AfKvSyEciJ-Jp7LufS2xcetrc8L9RQcJdOEn0d1JlFFJGA&oe=68414F94&_nc_sid=5b3566)

## 📊 Objetivo

Este proyecto busca analizar un conjunto de datos reales de propinas en un restaurante para identificar los factores que más influyen en la cantidad de propina entregada, y así proponer estrategias para aumentarlas. Usamos técnicas de ETL, análisis exploratorio y visualización de datos con `pandas`.

## 🛠️ Tecnologías Utilizadas

- Python 🐍
- Pandas 🐼
- Jupyter Notebook 📒
- Matplotlib & Seaborn 📈
- VS Code 💻

## 🔄 Proceso ETL

1. **Extracción**: Carga de los datos en formato `.csv`.
2. **Transformación**:
   - Limpieza de datos.
   - Formateo de variables.
   - Generación de nuevas columnas (por ejemplo: porcentaje de propina).
3. **Carga**: Los datos limpios y enriquecidos son analizados con pandas.

## 📌 Variables Analizadas

- Sexo del cliente
- Día de la semana
- Momento del día (almuerzo o cena)
- Tamaño del grupo
- Porcentaje de propina
- Fumador / no fumador
- Total de la cuenta

## 📈 Resultados Clave

- Los grupos más pequeños tienden a dejar mayores porcentajes de propina.
- Las cenas generan propinas más altas que los almuerzos.
- Los clientes no fumadores suelen dejar mejores propinas.
- El día domingo es el más rentable en propinas.

## 💡 Recomendaciones

- Incentivar turnos en cena para meseros con mejor desempeño.
- Diseñar promociones especiales los domingos.
- Capacitar al personal en atención a grupos pequeños y parejas.

## 🧠 Archivos del Proyecto

| Archivo | Descripción |
|--------|-------------|
| `etl_tips.ipynb` | Limpieza y transformación de los datos |
| `eda_tips.ipynb` | Análisis exploratorio de los datos |
| `reporte_final.pdf` | Conclusiones y recomendaciones |
| `data/tips.csv` | Dataset original |


## 📬 Contacto

- 📧 **Email**: angeltroncoso2019@outlook.es  
- 💼 **LinkedIn**: [linkedin.com/in/angeltroncoso](https://linkedin.com/in/angeltroncoso)  
- 🐱 **GitHub**: [@angel-data](https://github.com/angel-data)

---

⭐️ Si te gustó este proyecto, no olvides darle una estrella al repositorio.

