# ☀️ Medidor Solar LabVolt

Aplicación web y móvil para calcular **irradiancia solar (W/m²)** a partir del voltaje medido por un **piranómetro LabVolt**.

Desarrollado para prácticas de laboratorio en **Ingeniería en Energías Renovables**.

## Autor

**Ing. Braulio Aldair Gutierrez G.**

## Descripción

Esta aplicación permite convertir mediciones de **milivolts (mV)** provenientes de un piranómetro en **irradiancia solar (W/m²)**.

La conversión se realiza usando la sensibilidad del sensor:

Sensibilidad del piranómetro:

10.55 µV / (W/m²)

Ecuación utilizada:

Irradiancia (W/m²) = (mV × 1000) / 10.55

## Funciones

* Calculadora de irradiancia solar
* Medidor gráfico tipo gauge
* Cambio de color según nivel de irradiancia
* Registro de mediciones
* Exportación de datos en formato CSV
* Interfaz optimizada para celular
* Aplicación instalable (PWA)

## Uso en prácticas

1. Medir el voltaje del piranómetro en **milivolts (mV)**
2. Introducir el valor en la aplicación
3. Presionar **Calcular**
4. Obtener la **irradiancia solar en W/m²**
5. Guardar las mediciones en **CSV** para análisis posterior

## Rangos de irradiancia

| Irradiancia    | Condición       |
| -------------- | --------------- |
| < 300 W/m²     | Baja radiación  |
| 300 – 700 W/m² | Radiación media |
| > 700 W/m²     | Alta radiación  |

## Archivos del proyecto

```
piranometro.html
utld.png
renders.png
README.md
```

## Uso académico

Este proyecto fue desarrollado como herramienta didáctica para el **laboratorio de energía solar**.

Puede ser utilizado por estudiantes para:

* prácticas de medición de radiación solar
* registro de datos experimentales
* análisis de irradiancia

## Licencia

Uso educativo y académico.
