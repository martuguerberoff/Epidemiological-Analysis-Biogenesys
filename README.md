# 📊 Epidemiological-Analysis-Biogenesys
Análisis de datos epidemiológicos y estrategia de expansión de mercado utilizando Python, SQL y Power BI. 
Proyecto académico | SoyHenry | 2025


👥 Realizado por Martina Guerberoff


🎯 Objetivo general del proyecto

Desarrollar un modelo analítico integral que identifique las ubicaciones óptimas de expansión corporativa de Biogenesys en el contexto post-pandémico, y que permita visualizar oportunidades de mercado y maximizar el impacto sanitario.

🛡️ Objetivos específicos 

1. Limpiar y transformar los datos crudos en un Dataset unificado de alta calidad.
2. Realizar un análisis exploratorio de los datos que, a través de la identificación de variables clave y correlaciones entre las mismas, permita desarrollar hipótesis y establecer insights de negocio.
3. Desarrollar un algoritmo de clasificación lógica para categorizar a los países en tres segmentos: Expansión, Asociación estratégica y Suficiencia.
4. Diseño de un tablero interactivo que permita a los directivos de Biogenesys visualizar oportunidades de expansión.
5. Establecer conclusiones precisas y concretas que favorezcan la toma de decisión estratégica.


🚀 Alcance del proyecto

- Ingeniería de Datos (ETL): Implementación de un pipeline de procesamiento riguroso utilizando Python (Pandas y NumPy) para la carga, limpieza, filtrado y estandarización de datos demográficos y epidemiológicos.
- Análisis Exploratorio (EDA): Ejecución de estadística descriptiva y visualizaciones gráficas para identificar patrones, detectar anomalías y validar hipótesis de negocio sobre el conjunto de datos crudos.
- Modelado y Segmentación: Desarrollo de un algoritmo de clasificación lógica y definición de umbrales cuantitativos para categorizar a los países en tres segmentos de mercado.
- Visualización Ejecutiva: Diseño y construcción de un tablero interactivo en Power BI, siendo una herramienta de simulación de escenarios con capacidad de navegación desde una vista global hasta el detalle por país.
- Estrategia Corporativa: Formulación de conclusiones estratégicas y recomendaciones basadas en evidencia cuantitativa para guiar a la directiva de Biogenesys en la instalación de nuevos laboratorios.

⚙️ Stack Tecnológico

- Procesamiento de Datos (ETL): **Python** (Uso de librerías como Pandas y NumPy para la extracción, limpieza, filtrado y estandarización de datos demográficos y epidemiológicos).
- Análisis Exploratorio (EDA) y Modelado: **Python** (Cálculo de estadísticas descriptivas, validación de hipótesis y estructuración matemática del algoritmo de segmentación territorial).
- Visualización y Business Intelligence: **Power BI** (Desarrollo del tablero interactivo, diseño de interfaz para la simulación de escenarios corporativos y navegación de datos a nivel geográfico).

🧠 Principales hallazgos

- Alta volatilidad en los registros de los datos epidemiológicos --> Biogenesys necesita una cadena de suministro que soporte estos “shocks” de demanda masiva.
- Correlación critica (0.74) entre la prevalencia de diabetes y la densidad de población --> Biogenesys debe priorizar la expansión en las zonas de alta prevalencia de diabetes tanto para testear como para prevenir muertes.
- Correlación directa entre el PBI per cápita y la estructura sanitaria --> Los países que tienen el PBI per cápita más alto se encuentran en el top 3 de países con mayor vacunación por cada 100 mil habitantes.
- Deficiente estructura sanitaria general en los paises de LATAM con promedios de indicadores de la capacidad del sistema de salud bajos en comparación a los promedios mundiales --> Biogenesys debe instalar sus laboratorios privados en los países con pocos médicos, ya que se encuentran saturados y de esta forma se liberaría la carga a los hospitales públicos.

🧠 Matriz de oportunidades:

Definición de umbrales para la clasificación lógica de los 6 países en 3 segmentos:
    🔴Expansión: Países con insuficiente cobertura de vacunación (<170mil dosis/1000hab) o Tasa de Letalidad Crítica (> 2.5% < 40%).
    
    🟡Asociación Estratégica: Países con cobertura de vacunación controlada (entre 170mil y 200mil dosis/1000hab) y Tasa de Letalidad Controlada (<= 2.5%).
    
    🟢Suficiencia: Países con cobertura de vacunación exitosa (>200mil dosis/100mil hab) y Tasa de Letalidad Controlada (<= 2.5%).

Conclusiones:
    🔴Expansión: Mercados prioritarios para nuevos laboratorios. Prioridad Crítica: Brasil, México y Perú (justificación en el proyecto).
    Acción Recomendada: La expansión de laboratorios aquí es mandatoria. Se requiere infraestructura de laboratorios externos privados como Biogenesys para colaborar con la deficiente atención del sistema público y para lograr una producción local masiva que logre abastecer la inmensa demanda interna. Podrán buscarse contratos gubernamentales para suplir la falta de infraestructura estatal.
    
    🟡Asociación Estratégica: Oportunidades de Unión. Oportunidad Media: Colombia (justificación en el proyecto).
    Acción Recomendada: Asociación Estratégica. La vía más eficiente es la alianza con infraestructura local existente para elevar sus métricas al nivel de los países desarrollados sin incurrir en costos de construcción total.
    
    🟢Suficiencia: Mercados que no necesitarían una intervención. Países estabilizados: Argentina y Chile (justificación en el proyecto).
    Acción Recomendada: Monitoreo: Evitar la sobreinversión en infraestructura física. El foco debe limitarse al mantenimiento comercial, ya que el mercado está maduro y cubierto.



