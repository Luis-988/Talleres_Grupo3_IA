# ia
Inteligencia Artificial - Ingeniería de Sistemas - Universidad del Norte - Eduardo Zurek, Ph.D.

## Taller 06: Reducción de dimensiones

El notebook está en `Taller #6/taller_06_reduccion_dimensiones.ipynb`.

El dataset WISDM se descarga desde el enlace del taller o desde:
https://archive.ics.uci.edu/static/public/507/wisdm+smartphone+and+smartwatch+activity+and+biometrics+dataset.zip

Después de extraer `wisdm-dataset.zip`, se debe copiar su carpeta `arff_files` en `data/arff_files/`, conservando estas subcarpetas:

```text
data/arff_files/phone/accel
data/arff_files/phone/gyro
data/arff_files/watch/accel
data/arff_files/watch/gyro
```

El análisis usa los voluntarios `1607`, `1623` y `1641`. Los archivos del dataset y los ZIP están excluidos mediante `.gitignore`.
