# Proyecto-Individual-2

# <h1 align="center">**`Informe sobre el Comportamiento de las Telecomunicaciones a Nivel Nacional`**</h1>

<p align='center'>
<img src ="[(https://es.m.wikipedia.org/wiki/Archivo:Claro.svg)](https://upload.wikimedia.org/wikipedia/commons/0/0c/Claro.svg)">
<p>
  
Análisis Estratégico Claro

# ✏️ Descripción del proyecto
Este repositorio contiene el Dashboard desarrollado en Power BI Desktop para el análisis estratégico de las telecomunicaciones en Argentina, con foco en los accesos a internet. El informe visualiza tendencias históricas, participación por tecnologías, objetivos de crecimiento y cobertura geográfica, usando los últimos datos abiertos de ENACOM del 2do trimestre de 2024.

# 🔎 Objetivos principales:

- Analizar la evolución de los accesos por tecnología (ADSL, Cablemodem, Fibra Óptica) a través del tiempo.

- Medir el KPI obligatorio: crecimiento mínimo de 2% de accesos por cada 100 hogares por provincia en el próximo trimestre.

- Proponer y visualizar tres KPIs adicionales: participación de Fibra Óptica en el AMBA, cuota de mercado de Fibra óptica y cuota de mercado de Cablemodem por provincia.

- Identificar oportunidades de despliegue y mejora en provincias menos saturadas.

# 🗂️ Estructura del repositorio

Proyecto-Individual-2/

├── Internet.xlsx         # Archivo de datos original con varias hojas

├── Proyecto Integrador 2.pbix   # Archivo de Power BI (modelo + visualizaciones)

├── EDA.ipynb                  # Archivo de Jupiter Notebook que contiene el Analisis Exploratorio de los datos

└── README.md                 # Documentación (este archivo)

# ⚙️ Tecnologías y Herramientas

- **Power BI Desktop** (versión 2.139.2054.0 o superior)

- **Excel** (para preparar y revisar datos)

- **DAX** (medidas calculadas para KPIs)

- **Jupyter Notebook** (para el análisis exploratorio)
  
- **Python 3.19** (librerías: Pandas, Matplotlib y Seaborn)

# 🔁 Tranformaciones del Excel

- Eliminé los datos duplicados de la hoja Dial-BAf y todas las celdas que estaban vacías, que si fuera de otro modo, complicarían las tareas en Power Bi debido a que pesaba más de lo que podía soportar la aplicación.
- Eliminé últimas 2 filas de la hoja Accesos por Tecnología ya que eran un mensaje ("Los datos provinciales no coinciden a nivel nacional, ya que se rincorporó información que no contien apertuta a nivel geográfico.") que no tenía valor ni para mi analisis ni para mi Dashboard.

# 📥 Instalación y Uso
```
git clone https://github.com/JnPFernandez/Proyecto-Individual-2.git
cd Proyecto-Individual-2
```
- Abrir el proyecto en Power BI Desktop

Abrir pbix/Proyecto Integrador 2.pbix.

- Actualizar orígenes de datos

En el panel "Transformar datos", verificar las rutas al archivo data/Internet.xlsx.

Aplicar transformaciones y refrescar el modelo.

- Explorar el informe 

Navegar entre las cuatro pestañas: Presentación, Accesos por Tecnología, Accesos por cada 100 Hogares y Banda Ancha – Dial Up.

# 📊 Descripción de Páginas

- Presentación: Portada con descripción visual del proyecto y botones de navegación.

- Accesos por Tecnología: Línea de tiempo de ADSL, Cablemodem y Fibra Óptica; participation por provincia de Cablemodem y Fibra óptica, y KPI de Porcentaje de Accesos de Fibra óptica que pertenecen al AMBA según los últimos datos.

- Accesos por cada 100 Hogares: Evolución comparada con el objetivo de 2% de crecimiento.

- Banda Ancha – Dial Up: Mapa coroplético sobre el crecimiento en los accesos en cada provincia y diagrama de árbol mostrando distribución total de accesos del último trimestre.

# 🎯 KPIs Clave

- Crecimiento de accesos por 100 hogares del %2 para el próximo trimestre

- Porcentaje de Accesos de Fibra óptica que pertenecen al AMBA según los últimos datos 

- Cuota de mercado de Cablemodem por provincia

- Cuota de mercado de Fibra óptica por provincia

# ℹ️ Fuentes:

https://www.enacom.gob.ar

https://www.redusers.com/noticias/que-operador-de-telefonia-celular-tiene-mejor-cobertura-en-cada-provincia/#:~:text=Utilizando%20estos%20datos%2C%20fuimos%20a,75%20por%20ciento%20en%20promedio

# 📬 Contacto

Nombre: Juan Pablo Fernández

Correo: juanpablofernandez132@gmail.com

LinkedIn: linkedin.com/in/juan-pablo-fernández-608a95217/
