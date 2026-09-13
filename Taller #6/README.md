# Taller 06: Reduccion de dimensiones

## Ejecucion

Andres Serrano y Luis Robles

1. Abre `taller_06_reduccion_dimensiones.ipynb` en VS Code o Jupyter.
2. Ejecuta la celda de instalacion para instalar UMAP:

   ```python
   %pip install umap-learn
   ```

3. Descarga `wisdm-dataset.zip` y extrae la carpeta `arff_files` en:

   ```text
   Talleres_Grupo3_IA/data/arff_files/
   ```

   Deben existir estas carpetas:

   ```text
   data/arff_files/phone/accel/
   data/arff_files/phone/gyro/
   data/arff_files/watch/accel/
   data/arff_files/watch/gyro/
   ```

4. Ejecuta las celdas en orden. El notebook analiza los voluntarios `1607`, `1623` y `1641`.

El dataset no se sube a GitHub por su tamaño. Los warnings de MDS y UMAP son informativos y no impiden la ejecucion.
