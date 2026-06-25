# Tableau: Análisis de Indicadores Académicos y Dinámica Demográfica de la Educación en Argentina (2023)

Este repositorio contiene un proyecto práctico de Inteligencia de Negocios (BI) desarrollado en **Tableau** enfocado en la centralización, auditoría y análisis exploratorio del sistema educativo formal de la República Argentina para el ciclo 2023. El tablero consolida múltiples dimensiones de control del sector público: tasas de egreso por ciclos tradicionales, deserción o desgranamiento estudiantil en etapas críticas, impacto de los programas de terminalidad para adultos y concentración demográfica por regiones político-territoriales.

---

## 📊 Visualización Interactiva del Dashboard

Para desplegar la interfaz gráfica de forma directa en la documentación de tu portafolio, guarda la captura de pantalla de tu lienzo interactivo en la raíz de este repositorio con el nombre exacto de `dashboard_educacion.png`:

![Dashboard de Educación Argentina 2023](<img width="1457" height="576" alt="image" src="https://github.com/user-attachments/assets/3ef300e3-2ae7-4b70-acb5-ea1a62e21afc" />)

🔗 **[Interactuar con el Tablero en Vivo en Tableau Public](https://public.tableau.com/app/profile/maria.del.cielo.robledo/viz/DataArgentinaEducacion/DATOSEDUCACION)**

---

## 📈 Componentes y Métricas del Tablero

El diseño de la interfaz organiza la información utilizando técnicas de *Data Storytelling* para facilitar la identificación inmediata de alertas operativas en el sistema escolar:

### 1. Control de Egresos por Niveles y Terminalidad de Adultos
* **Embudo de Matrícula General (EGRESADOS 2023):** Gráfico de barras que compara de forma directa el volumen absoluto de alumnos que finalizan los ciclos Primario, Secundario y Superior, permitiendo evaluar cuantitativamente la pérdida de matrícula a lo largo de la trayectoria educativa tradicional.
* **Sistema de Adultos:** Segmentación analítica que mide el volumen de egresados consolidados frente a los estudiantes activos del nivel secundario, reflejando el impacto de los programas de terminalidad e inserción formativa.

### 2. Dinámica Demográfica y Densidad Geográfica
* **Distribución Provincial (Burbujas Empacadas):** Representación gráfica que aísla de forma visual los centros de masa poblacionales. Resalta inmediatamente a la **Provincia de Buenos Aires** (con más de 3.6 millones de estudiantes) y al **Conurbano** (con más de 2.2 millones) como las regiones de mayor demanda de infraestructura pedagógica del país.
* **Repeticiones por Provincia Primaria:** Gráfico de barras horizontales ordenadas de manera descendente que expone las frecuencias de eventos por provincias, facilitando auditorías de control territorial en el rendimiento académico primario.

### 3. Eficiencia Interna y Desgranamiento (*Repitencia y Abandono*)
* **Rango Etario de la Matrícula:** Histograma de frecuencias que distribuye la masa estudiantil por franjas de edad, evidenciando un pico de concentración crítico en el rango de **20-29 años**.
* **Análisis Estadístico de Pérdida (Primaria vs Secundaria):** Gráficos de barras que contrastan de forma paralela la matrícula total frente a los indicadores de fricción: alumnos *Repitentes* y alumnos *Salidos* (abandono). El modelo expone visualmente que el nivel secundario concentra los mayores desafíos de retención y vulnerabilidad del sistema.

---

## 🛠️ Conceptos Técnicos Aplicados en Tableau

* **Visualizaciones No Cartesianas (*Packed Bubbles*)**: Implementación de gráficos de burbujas empacadas para codificar magnitudes mediante el tamaño proporcional de esferas. Esta técnica optimiza el uso del lienzo al permitir comparar densidades volumétricas complejas de forma compacta sin necesidad de recurrir a mapas geográficos saturados.
* **Estructuras de Ordenamiento Dinámico Descendente**: Configuración de clasificaciones automáticas basadas en variables de agregación cuantitativa, garantizando que el ojo del tomador de decisiones se dirija de forma secuencial hacia las provincias o categorías con mayores frecuencias de interés de manera inmediata.
* **Sincronización y Narrativa Visual (*Dashboard Layout*)**: Integración de gráficos cuantitativos continuos (histogramas), categóricos univariados y diagramas de composición relacional bajo un esquema de proporciones balanceado que prioriza la legibilidad y la consistencia analítica.
