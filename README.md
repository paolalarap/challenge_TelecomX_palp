CHALLENGE ALURA LATAM TELECOMX
## 👋 **Sobre el Proyecto**

Este proyecto corresponde a un análisis completo de **evasión de clientes (churn)** para la empresa ficticia **TelecomX**.  
El objetivo fue identificar patrones de comportamiento, variables críticas y factores asociados a la cancelación de servicios, utilizando datos reales obtenidos desde una API.

El trabajo demuestra habilidades en:

- Manipulación y limpieza de datos  
- Análisis exploratorio (EDA)  
- Transformación y normalización de estructuras JSON  
- Identificación de inconsistencias  
- Análisis estadístico descriptivo  
- Visualización de datos  
- Interpretación de resultados orientada al negocio  

---

## 🧠 **Habilidades Demostradas**

### **✔️ Extracción de datos desde API**
- Uso de `requests` para consumir endpoints.
- Conversión de JSON anidado a DataFrame con `pd.json_normalize()`.

### **✔️ Limpieza y transformación**
- Detección y manejo de valores nulos, vacíos y duplicados.
- Estandarización de nombres de columnas.
- Conversión de tipos de datos.
- Creación de nuevas variables derivadas (ej. `cuenta_diaria`).
- Traducción de columnas para mejorar la interpretabilidad.

### **✔️ Análisis Exploratorio**
- Estadísticas descriptivas (media, moda, desviación estándar).
- Análisis de distribución de churn.
- Comparación de variables numéricas entre clientes que cancelan y los que no.
- Análisis de variables categóricas.
- Visualizaciones con `seaborn` y `matplotlib`.

### **✔️ Interpretación orientada al negocio**
- Identificación de segmentos con mayor riesgo de churn.
- Insights accionables para retención.
- Recomendaciones estratégicas basadas en datos.

---

## 📊 **Principales Hallazgos**

- Los clientes **nuevos** presentan mayor probabilidad de cancelar.  
- El plan económico es el más contratado, pero también muestra señales de inestabilidad.  
- Los clientes que cancelan suelen tener **menores cargos totales**, lo que indica que se van antes de consolidarse.  
- El tipo de contrato y método de pago influyen significativamente en la permanencia.  
- El segmento senior es minoritario y tiene bajo impacto en el churn.

---

## 🎯 **Recomendaciones Estratégicas**

- Implementar programas de onboarding y retención para clientes nuevos.  
- Revisar la propuesta de valor del plan económico.  
- Incentivar contratos de mayor permanencia mediante beneficios.  
- Mejorar servicios críticos como soporte técnico e internet.  
- Desarrollar un modelo predictivo de churn para priorizar acciones.

---

## 🛠️ **Tecnologías Utilizadas**

- Python  
- Pandas  
- NumPy  
- Requests  
- Seaborn  
- Matplotlib  
- Google Colab  

---

## 👩‍💻 **Sobre la Autora**

**Paola Lara**  
Estudiante del programa ONE EDUCATION, a través de Alura Latam
Chile  

Este proyecto refleja mi capacidad para transformar datos en insights accionables, comunicar hallazgos de forma clara y aportar valor estratégico a equipos de negocio y tecnología.



