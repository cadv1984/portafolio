# Análisis de Ventas y Desempeño – Alura Store Latam 🏬

Este proyecto analiza los datos de ventas de las 4 tiendas de **Alura Store Latam** para identificar cuál tiene menor eficiencia operativa. Basado en métricas como ingresos, reseñas, envío promedio y productos, se entrega una recomendación fundamentada sobre cuál tienda debería venderse para iniciar un nuevo emprendimiento.

---

## 📁 Estructura del Repositorio

AluraStoreLatam/
├── datos/
│ └── ventas_tiendas.csv # Archivo base con datos de ventas y envíos
├── notebooks/
│ └── AluraStoreLatam.ipynb # Notebook con análisis en Python (Pandas & Matplotlib)
├── readme.md # Este archivo explicativo
└── recomendacion_final.txt # Conclusión recomendada sobre la tienda a vender


---

## 🧠 Objetivo del Análisis

- Determinar la tienda de menor rendimiento (ingresos, satisfacción, logística)  
- Comparar rendimiento entre las 4 tiendas  
- Visualizar datos clave con al menos 3 gráficos distintos  
- Realizar propuesta final sobre cuál tienda vender al Sr. Juan/João

---

## 🛠️ Herramientas utilizadas

- **Python 3.x**
- **Pandas**: carga y manipulación de datos
- **Matplotlib**: creación de gráficos
- (Opcional) **Jupyter Notebook** para análisis interactivo

---

## 🚀 Cómo ejecutar el análisis

1. Clona el repositorio:
   ```bash
   git clone https://github.com/cadv1984/portafolio.git
   cd portafolio


2. Asegúrate de tener Python y las librerías necesarias:
pip install pandas matplotlib jupyter


3. Si deseas ejecutar en Jupyter:
jupyter notebook notebooks/AluraStoreLatam.ipynb

O puedes ejecutar un script equivalente si preparas uno separado.

Principales visualizaciones (mínimo 3)
Ingresos por tienda – gráfico de barras comparativo

Distrbución de categorías más vendidas – gráfico de torta o barras

Relación reseñas vs volumen de ventas – gráfico de dispersión

(Opcional) Envío promedio por tienda o productos top vendiendo

Los gráficos generados se pueden exportar desde el notebook hasta una carpeta graficos/.

📈 Conclusión y Recomendación (en recomendacion_final.txt)
El archivo contiene una explicación clara sobre cuál tienda debería venderse, apoyada en datos:

Tienda con menores ingresos netos

Peor evaluación por parte de clientes (reseñas)

Envío promedio más alto o peor logística

Bajo volumen de ventas por categoría

✅ Buenas prácticas
Validar los datos de entrada (ventas_tiendas.csv) antes de analizar

Etiquetar claramente los ejes en los gráficos generados

Proveer contexto breve antes de cada visualización

Incluir referencias de porcentaje, medias y comparaciones en el texto de conclusión

📄 Licencia
Este proyecto fue desarrollado como desafío educativo.
Distribuido bajo la Licencia MIT.

🙋 Créditos
Proyecto guía proporcionado por Alura Latam

Notebook: AluraStoreLatam.ipynb creado por Cristian Díaz (@cadv1984)


