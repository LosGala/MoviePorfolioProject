# Análisis de Datos de Películas

Este proyecto está diseñado para realizar un análisis exploratorio de un conjunto de datos sobre películas. El análisis incluye la limpieza de datos, la detección de valores faltantes y outliers, la visualización de relaciones entre variables y la identificación de patrones clave en los ingresos brutos y presupuestos de las películas.

## Contenido del Proyecto

- **Importación de Paquetes**: Utilización de bibliotecas `pandas`, `numpy`, `seaborn`, y `matplotlib` para el análisis y visualización de datos.
- **Carga de Datos**: Lectura de un archivo CSV con información sobre películas.
- **Análisis de Datos**:
  - Identificación de datos faltantes y eliminación de duplicados.
  - Detección de outliers y visualización de distribuciones.
  - Análisis de la relación entre ingresos brutos, presupuesto y calificación.
  - Generación de matrices de correlación para variables numéricas y categóricas.
- **Visualizaciones**:
  - Diagramas de caja, gráficos de dispersión, y matrices de correlación.
  - Análisis de compañías productoras por ingresos brutos.
  - Visualización de ingresos brutos en función de presupuestos y calificaciones.

## Instalación

Asegúrate de tener los siguientes paquetes instalados:

```bash
pip install pandas numpy seaborn matplotlib
```

## Uso

1. **Clona el Repositorio**:

   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
   ```

2. **Navega al Directorio del Proyecto**:

   ```bash
   cd tu-repositorio
   ```

3. **Coloca el Archivo CSV**:
   
   Asegúrate de que el archivo `movies.csv` esté en la ruta especificada en el código o actualiza la ruta en el script.

4. **Ejecuta el Código**:

   Puedes ejecutar el análisis en un entorno Jupyter Notebook o como un script de Python. Si utilizas Jupyter Notebook, asegúrate de ejecutar el código en celdas.

## Estructura del Código

1. **Importación de Bibliotecas**:
   - `pandas` para la manipulación de datos.
   - `numpy` para operaciones numéricas.
   - `seaborn` y `matplotlib` para visualización de datos.

2. **Carga y Exploración de Datos**:
   - Lectura de datos desde un archivo CSV.
   - Análisis inicial para detectar datos faltantes y outliers.
   - Ordenación y limpieza de datos.

3. **Análisis de Relaciones**:
   - Gráficos de regresión para explorar la relación entre variables.
   - Cálculo y visualización de matrices de correlación.

4. **Visualización de Resultados**:
   - Diagramas de dispersión y matrices de correlación.
   - Análisis de ingresos brutos por compañía y año.

## Resultados y Visualizaciones

- **Outliers y Distribución**: Visualización de la distribución de ingresos brutos y la detección de posibles outliers.
- **Relación Presupuesto vs Ingresos Brutos**: Análisis de cómo el presupuesto influye en los ingresos brutos.
- **Matrices de Correlación**: Exploración de relaciones entre todas las características numéricas y categóricas.

## Notas

- Asegúrate de tener el archivo `movies.csv` en la ubicación correcta.
- Personaliza el código según los datos específicos y las necesidades de análisis.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.
