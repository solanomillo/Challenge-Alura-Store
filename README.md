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

## 📊 Visualizaciones del Análisis

### 💵 Ingresos Totales por Tienda
<img src="https://github.com/solanomillo/Challenge-Alura-Store/blob/main/img/ingresos.png?raw=true" width="600"/>

### 🏷️ Distribución de Ventas por Categoría
<img src="https://github.com/solanomillo/Challenge-Alura-Store/blob/main/img/ventas_categorias.png?raw=true" width="600"/>

### 📦 Productos Más y Menos Vendidos
<img src="https://github.com/solanomillo/Challenge-Alura-Store/blob/main/img/ventas_productos.png?raw=true" width="600"/>

### ⭐ Calificaciones Promedio
<img src="https://github.com/solanomillo/Challenge-Alura-Store/blob/main/img/calificaciones.png?raw=true" width="600"/>

### 🚚 Costo de Envío Promedio
<img src="https://github.com/solanomillo/Challenge-Alura-Store/blob/main/img/envio_promedio.png?raw=true" width="600"/>

### 🔥 Heatmap de Ventas
<img src="https://github.com/solanomillo/Challenge-Alura-Store/blob/main/img/calor_df2.png?raw=true" width="600"/>

### ⚙️ Rendimiento General de las Tiendas
<img src="https://github.com/solanomillo/Challenge-Alura-Store/blob/main/img/rendimiento_df3.png?raw=true" width="600"/>


📸 Todos los gráficos se encuentran disponibles en la carpeta [`/img`](./img).


## 🛠️ Tecnologías Utilizadas  

| Herramienta | Uso Principal |
|--------------|---------------|
| 🐍 **Python 3** | Lenguaje principal |
| 📦 **Pandas** | Manipulación y análisis de datos |
| 📊 **Matplotlib** | Visualización de datos |
| 🌎 **Plotly Express** | Visualización interactiva de mapas y gráficos |
| 💻 **Google Colab / Jupyter** | Ejecución del análisis y visualizaciones |

---

## 🚀 Cómo Ejecutar el Proyecto  

1. Clona este repositorio en tu entorno local:  
   ```bash
   git clone https://github.com/tu-usuario/Challenge-Alura-Store.git
   cd Challenge-Alura-Store
   ```
2. Instala las dependencias necesarias:
   ```bash
   pip install pandas matplotlib plotly
   ```   
3. ## 🚀 Ejecutar el proyecto en Google Colab

1. Abre el siguiente enlace o copia la URL del notebook:  
   [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/solanomillo/Challenge-Alura-Store/blob/main/AluraStoreLatam.ipynb)

2. Una vez abierto, selecciona **“Conectar”** en la esquina superior derecha.

3. Ejecuta las celdas una por una usando **Ctrl + Enter** o **Shift + Enter**.

4. Si el notebook usa datos externos, asegúrate de subir los archivos CSV a Colab:
   ```python
   from google.colab import files
   uploaded = files.upload()
   ```
👨‍💻 Autor

Julio Solano
📧 [Tu correo o contacto profesional]
💼 Proyecto académico de análisis de datos – 2025
📍 Argentina

⭐ Si este proyecto te resultó útil, no olvides dejar una estrella en el repositorio.
