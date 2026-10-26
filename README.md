# Proyecto_Final_fase1_Herrera.xlsx

##  Conjunto de Datos para Analisis de Venta
Este conjunto de datos fue diseñado como parte de un Examen para el analisis de ventas de un comercio minorista 
El objetivo principal de este proyecto es **optimizar la toma de decisiones estratégicas** mediante el análisis 
detallado de los datos operativos del negocio.
En el entorno competitivo actual,**comprender los patrones de comportamiento de los clientes**,
**La eficiencia de los procesos y las tendencias de rendimiento es fundamental para maximizar la rentabilidad y mitigar riesgos**.

##  Origen del Dataset
* **Fuente:** Los datos provienen de [https://www.kaggle.com/datasets/dataregina/datasets-para-proyecto-bi].
* **Fecha de extracción:** [23/10/2026]
* **Periodo de los datos:** Cubre transacciones desde [31/01/2024] hasta [30/12/2024].
* **Descripción de los archivos:**
  * `categorias.csv`: Categorizacion de productos.
  * `clientes.csv`: ID y cartera de clientes.
  * `metodos_pago.csv`: ID y metodos de pago.
  * `productos.csv`: ID productos, precios y stock.
  * `ventas.csv`: Historial de compras y montos.
## Portabilidad y Configuración de Rutas

```text
Datos1coder
├── data/
│   ├── raw/                 # Archivos CSV originales (sin modificar)
│   │   ├── categorías.csv
│   │   ├── clientes.csv
│   │   ├── metodos_pago.csv
│   │   ├── productos.csv
│   │   └── ventas.csv
│   └── procesados/           # Archivos CSV limpios, transformados y remocion de columnas para disminuir la redundancia
│                             # Se combinaron tablas para enriquecer la tabla de hechos con atributos descriptivos    
│   └── notebooks/            # configuración de orígenes y consultas base en Power Query y Power Pivot
└──     README.md


   ```
