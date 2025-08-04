# Dashboard de Recursos Humanos - Power BI

![Dashboard de Recursos Humanos](https://github.com/JulioRubio6767/Dashboard-Recursos-Humanos--PowerBI/blob/main/assets/presupuesto%20pbi%20talento%20humano.gif)

📌 **Descripción General**  
Solución analítica para la gestión estratégica del capital humano, diseñada para empresas con alta rotación de personal donde la gestión eficiente de recursos humanos impacta directamente en la productividad organizacional.

🔍 **Características Principales**

### 📊 Módulo de Headcount
- Visualización del personal total, activo y cesado
- Cálculo automático de:
  - Tasa de rotación por periodo
  - Crecimiento/descenso de plantilla
  - Distribución por género y rangos etarios
- Identificación de áreas con mayor fluctuación

### 👥 Módulo de Distribución Organizacional
- Desglose jerárquico por:
  - Sede corporativa
  - Gerencia/Área funcional
  - Nivel organizacional
- Indicadores de:
  - Densidad organizacional
  - Proporción operativo/administrativo

💡 **Beneficios Clave**

**Para Dirección General**  
- Visión 360° del capital humano  
- Reducción de costos por rotación no planificada  
- Alineamiento estratégico de la fuerza laboral  

**Para RH**  
- Seguimiento de indicadores clave  
- Detección temprana de riesgos  
- Optimización de procesos de contratación  

🛠 **Tecnologías Utilizadas**  

| Herramienta | Función |
|-------------|---------|
| Power BI | Visualización interactiva |
| Power Query | Limpieza y transformación de datos |
| DAX | Medidas avanzadas (KPI) |
| Modelo en estrella | Relaciones dimensionales |

🔄 **Proceso de Implementación**  

1. **Extracción**: Conexión a fuentes HRIS (Excel, SAP, etc.)  
2. **Transformación**:  
   - Normalización de datos históricos  
   - Creación de tabla calendario  
   - Categorización de rangos etarios  
3. **Modelado**:  
   - Relación activa/inactiva (fechas ingreso/cese)  
   - Medidas DAX para cálculos acumulativos  
4. **Visualización**:  
   - Diseño responsive con paleta corporativa  
   - Interacciones cruzadas entre filtros  
5. **Distribución**:  
   - Publicación en Power BI Service  
   - Configuración de actualizaciones automáticas  

> **Nota diferenciadora**: Incluye lógica avanzada para distinguir entre personal activo/cesado considerando fechas históricas de análisis, permitiendo comparativas interperiodos precisas.
