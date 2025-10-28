# 🛒 Análisis de Ventas de Tiendas  

## 📊 Descripción del Proyecto  
Este proyecto analiza los datos de ventas de **cuatro tiendas** con el objetivo de ayudar al **Sr. Juan** a decidir qué tienda de su cadena **Alura Store** debe vender para iniciar un nuevo emprendimiento.  
A través de un estudio completo de **ingresos**, **productos**, **categorías**, **calificaciones**, **costos de envío** y **ubicaciones geográficas**, se extraen conclusiones basadas en datos reales y visualizaciones claras.

---

## 🧩 Estructura del Proyecto  

El repositorio se denomina **`Challenge-Alura-Store`** y contiene la siguiente estructura de archivos y carpetas:
```text
    📁 Challenge-Alura-Store/
  ├── AluraStoreLatam.ipynb # Archivo principal con el análisis completo (notebook)
  ├── 📁 img/ # Carpeta con las imágenes de los gráficos
  │ ├── calificaciones.png
  │ ├── envio_promedio.png
  │ ├── ingresos.png
  │ ├── ventas_categorias.png
  │ ├── ventas_productos.png
  │ ├── ventas_df1.png
  │ └── calor_df2.png
  | └── rendimiento_df3.png
  ├── 📄 README.md # Descripción general del proyecto
```

📂 **Descripción general:**
- `AluraStoreLatam.ipynb`: Contiene el análisis, procesamiento y visualización de los datos.  
- `img/`: Carpeta donde se almacenan los gráficos generados.
---

## 🧩 Estructura de los Datos  
Cada dataset contiene la siguiente información:

| Columna | Descripción |
|----------|-------------|
| 🛍️ `Producto` | Nombre del producto vendido |
| 🗂️ `Categoría del Producto` | Tipo o categoría del producto |
| 💰 `Precio` | Precio de venta |
| 🚚 `Costo de envío` | Costo asumido por el cliente |
| 📅 `Fecha de Compra` | Fecha en que se realizó la compra |
| 👤 `Vendedor` | Nombre del vendedor |
| 📍 `Lugar de Compra` | Ciudad donde se realizó la venta |
| ⭐ `Calificación` | Valoración del cliente |
| 💳 `Método de pago` | Medio utilizado para pagar |
| 🔢 `Cantidad de cuotas` | Número de cuotas del pago |
| 🌎 `lat` / `lon` | Coordenadas geográficas de la compra |

---

## 📈 Análisis Realizado  

1. 💵 **Ingresos Totales por Tienda**  
   Se sumaron los precios de venta para determinar el total de ingresos de cada tienda.

2. 🏷️ **Categorías de Productos Más y Menos Vendidas**  
   Se analizaron las categorías más populares y las que presentan menor rotación.

3. 📦 **Top y Bottom de Productos Vendidos**  
   Se identificaron los 3 productos más y menos vendidos por tienda.

4. ⭐ **Calificaciones Promedio de Clientes**  
   Se calculó el promedio de satisfacción de los clientes por tienda.

5. 🚚 **Costo de Envío Promedio**  
   Se determinó el costo medio de envío, considerando que lo paga el cliente.

6. 🗺️ **Análisis Geográfico (Extra)**  
   Se mapearon las ventas mediante coordenadas de **latitud** y **longitud**, identificando regiones con mayor concentración y rendimiento.

---

## 📊 Visualizaciones Incluidas  

✨ Gráficos y diagramas generados en el proyecto:  
- 📉 Gráfico de barras de ingresos por tienda.  
- 🥧 Gráficos de torta de categorías por tienda.  
- 🟩 Comparativas de productos más y menos vendidos.  
- 🌡️ Mapas de calor y dispersión geográfica con **Plotly**.  
- 📊 Gráficos de líneas de calificaciones promedio.  
- 💸 Gráficos horizontales de costos de envío.  

📸 Todos los gráficos se encuentran disponibles en la carpeta [`/img`](./img).


## 🛠️ Tecnologías Utilizadas  

| Herramienta | Uso Principal |
|--------------|---------------|
| 🐍 **Python 3** | Lenguaje principal |
| 📦 **Pandas** | Manipulación y análisis de datos |
| 📊 **Matplotlib** | Visualización de datos |
| 🌎 **Plotly Express** | Visualización interactiva de mapas y gráficos |
| 🧭 **Folium (opcional)** | Mapas interactivos y geolocalización |
| 💻 **Google Colab / Jupyter** | Ejecución del análisis y visualizaciones |

---

## 🚀 Cómo Ejecutar el Proyecto  

1. Clona este repositorio en tu entorno local:  
   ```bash
   git clone https://github.com/tu-usuario/Challenge-Alura-Store.git
   cd Challenge-Alura-Store
   ```
2. Instala las dependencias necesarias:
3. Abre el notebook principal
4. Ejecuta las celdas para visualizar los resultados y generar los gráficos.
