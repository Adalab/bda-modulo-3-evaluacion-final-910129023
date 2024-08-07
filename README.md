Evaluación Final - Módulo 3 📝

Este repositorio contiene la evaluación final del Módulo 3, donde se realizan análisis y visualización de datos a partir de dos conjuntos de datos relacionados con vuelos reservados y clientes. Durante el ejercicio hemos puesto en práctica los conocimientos adquiridos en el bootcamp de Data Analitycs desarrolado por ADALAB . 💜

# Estructura del Repositorio 📚

- **data/**: Contiene los archivos de datos utilizados en el análisis.
- **notebooks/**: Contiene el cuaderno de Jupyter donde se realiza la exploración, limpieza, visualización y análisis de datos.
- **requirements.txt**: Enumera las dependencias necesarias para ejecutar el proyecto.

## Configuración del Entorno

Para comenzar con el proyecto, asegúrate de tener instalado Python y Jupyter Notebook. Puedes instalar las dependencias necesarias utilizando el archivo `requirements.txt`:


### Fase 1:  Exploración y Limpieza: 🔍🧹
     # Descripcion de las columnas df 1. 

Year: El año en el que se registran los datos de vuelos. Esta columna permite observar la tendencia a lo largo de los años.

Month: El mes en el que se registran los datos de vuelos. Junto con el año, ayudan a analizar patrones mensuales de vuelos.

Flights Booked: Número total de vuelos que se han reservado. Esta información puede ayudar a medir la actividad de reservas de vuelos en un periodo determinado.

Flights with Companions: Número de vuelos que se han reservado con otros pasajeros (compañeros de viaje). Puede ser útil para entender si los viajeros prefieren volar solos o en compañía.

Total Flights: Suma total de los vuelos, que podría incluir tanto los vuelos reservados como aquellos volados. Esta columna presenta una visión general de la actividad de vuelo.

Distance: Distancia total cubierta por los vuelos, generalmente medida en millas o kilómetros. Esta métrica es útil para evaluar el alcance y la cantidad de desplazamiento realizado.

Points Accumulated: Número total de puntos acumulados durante el periodo, que podría estar relacionado con un programa de fidelización de aerolíneas. Esto proporciona información sobre beneficios potenciales de viaje.

Points Redeemed: Número de puntos que se han canjeado por recompensas, como boletos de avión, mejoras o servicios adicionales. Permite evaluar cuántos puntos han sido utilizados en lugar de solo acumulados.

Dollar Cost Points Redeemed: Costo en dólares de los puntos canjeados. Puede ilustrar el valor monetario de los puntos utilizados y ayudar a analizar el retorno de la inversión en un programa de fidelización.

        #  Descripción de las columnas df2

Country: País donde reside el cliente.

Province: Provincia o estado del cliente.

City Ciudad del cliente.

Postal Code: Código postal del cliente; puede ser útil para segmentar clientes geográficamente.

Gender: Género del cliente (e.g., masculino, femenino, no binario).

Education: Nivel educativo del cliente (e.g., secundaria, universitario, posgrado).

Salary: Ingresos del cliente; puede ayudar a entender su capacidad de gasto.

Marital Status: Estado civil del cliente (e.g., soltero, casado, divorciado).

Loyalty Card: Indica si el cliente tiene una tarjeta de fidelidad, lo que puede indicar compromiso con la marca.

CLV (Customer Lifetime Value): Valor del cliente a lo largo de su relación con la empresa, importante para la estrategia de marketing.

Enrollment Type: Tipo de inscripción que el cliente eligió (e.g., online, en tienda).

Enrollment Year: Año en el que el cliente se inscribió.

Enrollment Month: Mes en el que el cliente se inscribió.

Cancellation Year: Año en el que el cliente canceló su relación o servicio con la empresa.

Cancellation Month: Mes en el que el cliente canceló.

Exploración Inicial: Se realizó una revisión de los datos para identificar valores nulos, atípicos y otras inconsistencias.
Limpieza de Datos: Eliminación o tratamiento de valores nulos y conversión de tipos de datos para asegurar la coherencia y corrección de los datos.

### Fase 2: Visualización  📊📈📉

Se crearon varias visualizaciones para responder a las siguientes preguntas:

Distribución de la cantidad de vuelos reservados por mes durante el año.
Relación entre la distancia de los vuelos y los puntos acumulados por los clientes.
Distribución de los clientes por provincia o estado.
Comparación del salario promedio entre diferentes niveles educativos de los clientes.
Proporción de clientes con diferentes tipos de tarjetas de fidelidad.
Distribución de los clientes según su estado civil y género.


### Fase 3: Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo💻🤓

Preparación de Datos: Se filtraron los datos para incluir únicamente las columnas relevantes.
Análisis Descriptivo: Cálculo de estadísticas descriptivas del número de vuelos reservados por nivel educativo.
Prueba Estadística: Se realizó un A/B testing para determinar diferencias significativas en el número de vuelos reservados.
Cómo Ejecutar el Análisis

📌 Conclusiones :
El proyecto es bastante abarcador, ya que pretende simular pruebas técnicas con el fin de estar mejor preparados al optar por oportunidades laborales relacionadas con el anàlisis de datos. Aunuqe presento estos resultados como muestra del avance que he alcanzado a lo largo de estas semanas de bootcamp he de dejar claro mi intensión de continuar trabajando en este y otros proyectos con el fin de obtimizar sus resultados y afianzar mis conocimientos. 
¡Gracias por revisar mi trabajo! Cualquier comentario o sugerencia es bienvenida! 




