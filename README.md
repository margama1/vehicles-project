# vehicles-project
Dashboard interactivo para análisis de ventas de vehículos

## Descripción del Proyecto
Esta aplicación web permite analizar un conjunto de datos de anuncios de venta de vehículos usando visualizaciones interactivas construidas con Streamlit. Los usuarios pueden explorar los datos de manera intuitiva a través de gráficos dinámicos.

## Funcionalidades
- **Histograma del Odómetro**: Visualiza la distribución de los valores del odómetro de los vehículos en venta
- **Gráfico de Dispersión**: Muestra la relación entre el odómetro y el precio de los vehículos
- **Interfaz Interactiva**: Botones que permiten generar las visualizaciones bajo demanda

## Lenguajes Utilizados
- Python
- Streamlit
- Pandas
- Plotly Express

## Cómo Ejecutar la Aplicación
1. Instalar las dependencias: `pip install -r requirements.txt`
2. Ejecutar la aplicación: `streamlit run app.py`
3. Abrir el navegador en `http://localhost:8501`

## Datos
La aplicación utiliza un conjunto de datos de vehículos (`vehicles_us.csv`) que contiene información sobre anuncios de venta de vehículos, incluyendo precios, odómetro, y otras características.