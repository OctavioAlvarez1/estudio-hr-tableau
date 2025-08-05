# 👩‍💼 HR Dashboard – Proyecto de Recursos Humanos en Tableau

Este proyecto consiste en el desarrollo de un **dashboard interactivo en Tableau** basado en un conjunto de datos sintéticos que simula información de Recursos Humanos. La visualización permite analizar aspectos demográficos, organizacionales, salariales y de desempeño del personal, con filtros dinámicos y vistas detalladas.

---

## 🎯 Objetivo del Proyecto

El objetivo principal es brindar a los responsables de RRHH una herramienta visual e intuitiva para:

- Supervisar contrataciones y desvinculaciones
- Comprender la composición demográfica de la empresa
- Detectar disparidades salariales y de rendimiento
- Identificar oportunidades de mejora organizacional

---

## 🧾 Dataset

El conjunto de datos fue generado con **Python** y la librería **Faker**, simulando 8.950 empleados. Incluye:

- Información personal: nombre, género, edad, ciudad, estado
- Detalles laborales: fecha de contratación y despido, puesto, departamento
- Evaluaciones: desempeño, educación, horas extra
- Salarios base y ajustados (por edad, género y nivel educativo)

📁 Archivo generado: `HumanResources.csv`

---

## 📊 Estructura del Dashboard

El tablero está dividido en **dos vistas principales**:

### 1. **Resumen General (HR | Summary)**

![Dashboard General](Imágenes/dashboard-summary.png)

Incluye:
- Total de empleados activos, contratados y dados de baja
- Evolución temporal de contrataciones y despidos
- Ranking por departamentos
- Distribución geográfica (HQ vs sucursales)
- Proporción de género
- Relación entre edad y educación
- Evaluación de desempeño según nivel educativo
- Comparación salarial entre géneros por nivel educativo
- Relación entre edad y salario por puesto

---

### 2. **Vista Detallada (HR | Details)**

![Dashboard Detallado](Imágenes/dashboard-details.png)

Incluye:
- Tabla completa de empleados con información clave
- Posibilidad de filtrar por múltiples campos (género, edad, departamento, etc.)
- Visualización del tiempo de permanencia por empleado

---

## 📈 Insights Relevantes

🔹 El 54% de los empleados son hombres, y el 46% mujeres.  
🔹 Los empleados con estudios de nivel **Bachelor** (licenciatura) predominan en casi todos los rangos etarios.  
🔹 Los salarios ajustados tienden a ser mayores para mujeres con **PhD**, lo que reduce brechas de género en niveles altos.  
🔹 El grupo etario **35-44 años** es el más numeroso dentro del personal.  
🔹 El 70% de los empleados trabaja en la sede central (HQ – Nueva York).  
🔹 La relación **educación vs desempeño** muestra que quienes tienen títulos de posgrado tienden a tener mejores evaluaciones.  

---

## 🛠️ Tecnologías Utilizadas

- **Python** (Pandas, NumPy, Faker)
- **Tableau Desktop / Public**
- **Photopea** (para íconos e interfaz visual)
- **Draw.io** y **Procreate** (mockups)

---

## ✍️ Autor

**Octavio Alvarez**  
📫 [LinkedIn](https://linkedin.com/in/octavio-alvarez-6a229b223)  


---

