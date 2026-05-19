# 📊 Proyecto 6 - Análisis de Telecomunicaciones ConnectaTel

## 📌 Objetivo del Proyecto

El objetivo de este proyecto es analizar el comportamiento de uso de los clientes de una empresa de telecomunicaciones llamada **ConnectaTel**, con operaciones en México y Colombia.

A través del análisis de llamadas, mensajes y planes contratados, se busca:

- Identificar patrones de consumo.
- Detectar comportamientos atípicos.
- Analizar diferencias entre segmentos de clientes.
- Comprender cómo influye el tipo de plan en el uso del servicio.
- Generar insights que ayuden a optimizar la oferta comercial y mejorar la experiencia del usuario.

---

# 🗂️ Datasets Utilizados

El proyecto utiliza tres fuentes principales de datos:

## 1. `plans.csv`
Información sobre los planes móviles disponibles:

- Precio del plan
- Minutos incluidos
- GB incluidos
- Costos adicionales

---

## 2. `users_latam.csv`
Información de los usuarios:

- Edad
- Ciudad
- País
- Fecha de registro
- Plan contratado
- Estado de churn

---

## 3. `usage.csv`
Registro de actividad de los usuarios:

- Duración de llamadas
- Mensajes enviados
- Longitud/cantidad de mensajes

---

# 🔍 Etapas del Análisis

Durante el desarrollo del proyecto se realizaron las siguientes etapas:

1. Carga y exploración de datos.
2. Limpieza y validación de datos.
3. Conversión y estandarización de tipos de datos.
4. Análisis exploratorio de datos (EDA).
5. Detección de valores atípicos.
6. Segmentación de usuarios.
7. Visualización de patrones de consumo.
8. Obtención de conclusiones e insights de negocio.

---

# 🛠️ Herramientas Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# ▶️ Cómo Ejecutar el Notebook

## Opción 1: Google Colab

1. Subir el archivo `.ipynb` a Google Colab.
2. Subir los datasets (`plans.csv`, `users_latam.csv`, `usage.csv`).
3. Ejecutar las celdas en orden.

---

# 🔄 Guía de Reproducción en Google Colab

1. Descargar o clonar este repositorio.

2. Abrir el archivo `.ipynb` en Google Colab:
   - Ingresar a: https://colab.research.google.com/
   - Seleccionar **Subir Notebook** y cargar el archivo del proyecto.

3. Subir los datasets necesarios:
   - `plans.csv`
   - `users_latam.csv`
   - `usage.csv`

4. Verificar que los archivos estén en la misma ruta del notebook o actualizar las rutas de lectura si es necesario.

5. Instalar dependencias (si aplica).

---

# 👩‍💻 Autor

Alejandra Castro  
Proyecto académico de Análisis de Datos.
