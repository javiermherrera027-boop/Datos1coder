# Proyecto_Final_fase1_Herrera.xlsx
Abrir el archivo xlsx, ir a la pestaña Datos, Consultas y conecciones, Actualizar todo.

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
  * `categorias.csv`  : Categorizacion de productos.
  * `clientes.csv`    : ID y cartera de clientes.
  * `metodos_pago.csv`: ID y metodos de pago.
  * `productos.csv    : ID productos, precios y stock.
  * `ventas.csv`      : Historial de ventas y montos.
## Diccionario de de Tablas y claves

1. Tabla: clientes
  • Descripción: Almacena la información maestra de los clientes.
  • Clave Primaria (PK): ID_Cliente. 
  • Reglas: Identificador único por cada cliente registrado. No admite valores nulos ni duplicados.

2. Tabla: producto.
  • Descripción: Catálogo de productos disponibles para la venta.
  • Clave Primaria (PK): ID_Producto. 
  • Reglas: Cada artículo posee un código unívoco.

3. Tabla: metodo_pago
  • Descripción: Distintos metodos de pago
  • Clave Primaria (PK): ID_Metodo 
  • Reglas: Cada metodo posee un código único

4. Tabla de Ventas: ventas.
  • Descripción: Registro transaccional de ventas.
  • Clave Primaria (PK): ID_Venta (PK compuesta o ID único de transacción).
  • Claves Foráneas (FK):
     	               ID_Cliente → clientes(ID_cliente).
	                   ID_Producto →  productos(ID_producto).
                       ID_Metodo → metodo_pago (ID_Metodo).

## Portabilidad y Configuración de Rutas

```Repositorio
javiermherrera027-boop/
├── datos1coder/
│   │         ├── Proyecto_Final_fase1Herrera.xlxs                 
│   │         ├── ReseñaEntrega1.md                  
│   │         ├── categorías.csv                     # Archivos CSV originales (sin modificar)
│   │         ├── clientes.csv                       # Archivos CSV originales (sin modificar)
│   │         ├── metodos_pago.csv                   # Archivos CSV originales (sin modificar)
│   │         ├── productos.csv                      # Archivos CSV originales (sin modificar)
│   │         └── ventas.csv                         # Archivos CSV originales (sin modificar)



   ```
