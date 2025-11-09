# 📊 Alura Store Latam - Análisis de Rendimiento de Tiendas

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/LordAguaKate/Store/blob/AnalisisGeografico/AluraStoreLatam.ipynb)

## 📋 Descripción del Proyecto

Este proyecto contiene un análisis exhaustivo de datos de 4 tiendas de la cadena **Alura Store** en Latinoamérica. El objetivo principal es evaluar el rendimiento de cada tienda mediante métricas clave de negocio para identificar oportunidades de mejora y tomar decisiones estratégicas informadas.

El análisis se realizó utilizando Python con bibliotecas de ciencia de datos y visualización, procesando datos de ventas, calificaciones de clientes, costos de envío y distribución geográfica.

---

## 🎯 Objetivos del Análisis

- **Evaluar el rendimiento financiero** de cada tienda mediante análisis de facturación
- **Identificar patrones de venta** por categoría de producto
- **Medir la satisfacción del cliente** a través de calificaciones promedio
- **Analizar la eficiencia logística** mediante costos de envío
- **Visualizar la distribución geográfica** de las ventas
- **Proporcionar recomendaciones estratégicas** basadas en datos

---

## 📊 Métricas Analizadas

### 1. **Ingresos Totales por Tienda**
- Tienda 1: $1,150,880,400
- Tienda 2: $1,116,343,500
- Tienda 3: $1,098,019,600
- Tienda 4: $1,038,375,700

### 2. **Calificación Promedio de Clientes**
- Tienda 3: 4.05 ⭐
- Tienda 2: 4.04 ⭐
- Tienda 4: 4.00 ⭐
- Tienda 1: 3.98 ⭐

### 3. **Costo de Envío Promedio**
- Tienda 4: $23,459.46 (más económico)
- Tienda 3: $24,805.68
- Tienda 2: $25,216.24
- Tienda 1: $26,018.61

### 4. **Categorías Más Vendidas** (todas las tiendas)
1. Muebles
2. Electrónicos
3. Juguetes
4. Electrodomésticos
5. Deportes y diversión

---

## 🛠️ Tecnologías Utilizadas

- **Python 3.x**
- **Pandas** - Manipulación y análisis de datos
- **Matplotlib** - Visualización de datos estática
- **Seaborn** - Visualizaciones estadísticas avanzadas
- **Folium** - Mapas interactivos y visualización geográfica
- **Jupyter Notebook** - Entorno de desarrollo interactivo

---

## 📁 Estructura del Proyecto

```
Store/
│
├── AluraStoreLatam.ipynb    # Notebook principal con todo el análisis
├── README.md                 # Este archivo
└── data/                     # Datos cargados desde URLs remotas
    ├── tienda_1.csv
    ├── tienda_2.csv
    ├── tienda_3.csv
    └── tienda_4.csv
```

---

## 🚀 Cómo Ejecutar el Proyecto

### Opción 1: Google Colab (Recomendado)

1. Haz clic en el badge "Open in Colab" al inicio de este README
2. El notebook se abrirá en Google Colab
3. Ejecuta las celdas secuencialmente (Runtime > Run all)

### Opción 2: Entorno Local

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/LordAguaKate/Store.git
   cd Store
   ```

2. **Instala las dependencias:**
   ```bash
   pip install pandas matplotlib seaborn folium jupyter
   ```

3. **Ejecuta Jupyter Notebook:**
   ```bash
   jupyter notebook AluraStoreLatam.ipynb
   ```

4. **Ejecuta las celdas** en orden para ver el análisis completo

---

## 📈 Análisis Incluidos

El notebook contiene los siguientes análisis detallados:

### 1. **Análisis de Facturación**
- Comparación de ingresos totales entre las 4 tiendas
- Gráfico de barras con valores en millones de pesos

### 2. **Ventas por Categoría**
- Distribución de ventas por categoría de producto
- Comparación entre tiendas
- Gráfico circular (pie chart) de distribución total

### 3. **Calificación Promedio**
- Análisis de satisfacción del cliente
- Correlación entre calificación y costo de envío
- Gráfico de dispersión (scatter plot)

### 4. **Productos Más y Menos Vendidos**
- Top 5 productos más vendidos por tienda
- Top 5 productos menos vendidos por tienda
- Gráficos de barras horizontales

### 5. **Análisis de Costos de Envío**
- Comparación de costos promedio de envío
- Impacto en la satisfacción del cliente

### 6. **Análisis Geográfico**
- Mapa de calor (heatmap) de ventas
- Distribución geográfica por tienda
- Mapas interactivos con Folium
- Clustering de puntos de venta

---

## 🔍 Principales Hallazgos

### ✅ Fortalezas Identificadas

- **Tienda 1**: Líder en facturación con más de $1,150M
- **Tienda 3**: Mejor calificación promedio (4.05 estrellas)
- **Tienda 4**: Costos de envío más competitivos
- **Categoría Muebles**: Categoría más vendida en todas las tiendas

### ⚠️ Áreas de Mejora

- **Tienda 1**: Calificación más baja (3.98 estrellas) y costos de envío más altos
- **Tienda 4**: Menor facturación total
- Oportunidad de optimizar costos logísticos en Tiendas 1, 2 y 3
- Potencial de crecimiento en categorías de menor venta

### 💡 Recomendaciones Estratégicas

1. **Optimizar costos de envío** en Tiendas 1, 2 y 3 para mejorar competitividad
2. **Replicar estrategias** de la Tienda 3 (mejor calificada) en otras tiendas
3. **Fortalecer inventario** en categorías de alto rendimiento (Muebles, Electrónicos)
4. **Analizar la estrategia logística** de la Tienda 4 para reducir costos
5. **Implementar programas de fidelización** para mejorar calificaciones

---

## 📊 Visualizaciones Destacadas

El notebook incluye múltiples visualizaciones profesionales:

- 📊 Gráficos de barras con formato de millones
  
  <img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/fc5502c0-0a27-49a3-8c63-474c724cd935" />

- 🥧 Gráficos circulares de distribución por categoría
  
  <img width="1081" height="890" alt="image" src="https://github.com/user-attachments/assets/b67d8860-673a-4b60-b433-4ae658737356" />

- 📈 Gráficos de dispersión para análisis de correlación
  
  <img width="1180" height="889" alt="image" src="https://github.com/user-attachments/assets/65ad4562-e5dd-40e3-bdfa-0e3ccbb023c9" />

- 🗺️ Mapas de calor geográficos interactivos
  
  <img width="2243" height="1130" alt="image" src="https://github.com/user-attachments/assets/eb81d5fc-0d44-440f-9fc0-9f12f0de2d8d" />


- 📍 Mapas de clustering con información detallada por punto
  
  <img width="2057" height="1105" alt="image" src="https://github.com/user-attachments/assets/3409b462-f3f3-4b63-bac1-3b26383d0558" />


---

## 📝 Fuente de Datos

Los datos provienen del **Challenge de Data Science de Alura Latam** y están disponibles públicamente en:

- [Repositorio de datos](https://github.com/alura-es-cursos/challenge1-data-science-latam)

Cada dataset contiene información sobre:
- Producto vendido
- Categoría del producto
- Precio de venta
- Costo de envío
- Fecha de compra
- Vendedor
- Lugar de compra (ciudad)
- Calificación del cliente (1-5 estrellas)
- Método de pago
- Cantidad de cuotas
- Coordenadas geográficas (latitud y longitud)

---

## 👥 Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar este análisis:

1. Haz un Fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/NuevaCaracteristica`)
3. Commit tus cambios (`git commit -m 'Agregar nueva característica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un Pull Request

---

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

---

## 📧 Contacto

**Autor**: LordAguaKate  
**Repositorio**: [github.com/LordAguaKate/Store](https://github.com/LordAguaKate/Store)

---

## 🙏 Agradecimientos

- **Alura Latam** por proporcionar los datasets del challenge
- Comunidad de Python y Data Science por las excelentes bibliotecas
- Todos los contribuidores que ayuden a mejorar este proyecto

---

**⭐ Si este proyecto te resultó útil, considera darle una estrella en GitHub!**
