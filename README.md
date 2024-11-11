# 📹 Análisis de tendencias en Youtube

## Descripción del Proyecto
La cadena de gimnasios Model Fitness está desarrollando una estrategia de interacción con clientes basada en datos analíticos. 
Uno de los problemas más comunes que enfrentan los gimnasios y otros servicios es la pérdida de clientes. 
Los indicadores de pérdida varían de un campo a otro. En el caso de un gimnasio, tiene sentido decir que un/a cliente se ha ido si no viene durante un mes. Por supuesto, es posible que estén en Cancún y retomen sus visitas cuando regresen, pero ese no es un caso típico. Por lo general, si un/a cliente se une, viene varias veces y luego desaparece, es poco probable que regrese.

## Objetivos
El objetivo principal es combatir la cancelación de membresías mediante el análisis de datos históricos de clientes y la elaboración de una estrategia de retención efectiva.
  
## Dataset
- `'Churn'` — la cancelación para el mes en cuestión
- `'gender'`.
- `'Near_Location'` — si el/la usuario/a vive o trabaja en el vecindario donde se encuentra el gimnasio.
- `'Partner'` — si el/la usuario/a trabaja en una compañía asociada (el gimnasio tiene empresas asociadas cuyos empleados obtienen descuentos; en esos casos el gimnasio almacena información sobre los empleadores de los clientes).
- `Promo_friends` — si el/la usuario/a originalmente se inscribió mediante una oferta “trae a un/a amigo/a” (se utilizó el código promocional de un/a amigo/a cuando pagaron el primer abono).
- `'Phone'` — si el/la usuario/a aportó el número de teléfono.
- `'Age'`.
- `'Lifetime'` — el tiempo (en meses) desde que el/la usuario/a llegó por primera vez al gimnasio.
- Datos del registro de visitas y compras y datos sobre el estado actual de la membresía:
- `'Contract_period'` — 1 mes, 3 meses, 6 meses o 1 año.
- `'Month_to_end_contract'` — los meses que faltan hasta que expire el contrato.
- `'Group_visits'` — si el/la usuario/a participa en sesiones grupales.
- `'Avg_class_frequency_total'` — frecuencia media de visitas por semana a lo largo de la vida del cliente.
- `'Avg_class_frequency_current_month'` — frecuencia media de visitas por semana durante el mes en curso.
- `'Avg_additional_charges_total'` — cantidad total de dinero gastado en otros servicios del gimnasio: cafetería, productos deportivos, cosméticos, masajes, etc.

## Herramientas utilizadas
- **Python**: pandas, numpy, matplotlib, seaborn, sklearn
- **Jupyter Notebooks**: para análisis interactivo.

## Pasos de análisis
- **Paso 1**: Descargar e inspeccionar los datos sobre cancelación y características de los clientes.
- **Paso 2**: Realizar un análisis exploratorio de datos (EDA) para identificar tendencias, valores atípicos y relaciones entre variables.
- **Paso 3**: Construir modelos de clasificación (regresión logística y bosque aleatorio) para predecir la probabilidad de cancelación de un cliente en el mes siguiente.
- **Paso 4**: Utilizar el algoritmo de clustering K-means para identificar grupos de clientes con comportamientos similares y analizar sus características y tasas de cancelación.
- **Paso 5**: Extraer conclusiones y formular recomendaciones sobre cómo optimizar la estrategia de interacción y retención de clientes, incluyendo la identificación de grupos objetivo y medidas específicas para reducir la rotación.

## Conclusiones
Se caracteriza cada grupo por sus niveles de frecuencia de visita, participación en actividades grupales y gastos adicionales, y se proponen estrategias personalizadas para cada uno de ellos. Estas estrategias buscan aumentar la fidelidad y la satisfacción de los miembros, incluyendo promociones, programas de fidelización, encuestas y programas personalizados para satisfacer mejor sus necesidades.

**Nota**: Este proyecto fue desarrollado como parte de mi formación en el bootcamp de Tripleten en el área de análisis de datos.

## Visualizaciones
![image](https://github.com/user-attachments/assets/08063280-479b-4dcd-864d-21ab545744cd)
![image](https://github.com/user-attachments/assets/c3adf084-33f2-4a7f-aea4-ee518856c110)
![image](https://github.com/user-attachments/assets/2a52028a-0579-4246-851d-966355013812)
![image](https://github.com/user-attachments/assets/cc2c5281-bafd-429b-b864-87ec32783441)



