# Proyecto Final — Ciencia Computacional Intermedia (Tercer corte)

**Confiabilidad y planeación de capacidad de un servicio de inferencia de IA** (caso *AndesVision AI*).

Grupo 1: Henry Cantor, Santiago Fajardo, Sebastián Páez, Sebastián Acuña.

## Contenido

| Archivo | Descripción |
|---|---|
| `CCI_Proyecto_Final_Grupo2.ipynb` | Notebook principal (Partes A–G). |
| `CCI_Proyecto_Final_2026_3.pdf` | Enunciado del proyecto. |
| `solicitudes.csv` | 20 min de producción, una fila por solicitud (datos del grupo). |
| `monitoreo.csv` | 6000 minutos del entorno de pruebas (alertas D1, D2 e incidentes). |
| `solicitudes_validacion.csv` | Segunda ventana de producción. **Solo se usa en el ítem F6.** |

## Parámetros del grupo

`S = C1 + C2 = 4280006856`

| τ (ms) | ε | 1 − α | g | t1 (KB) | t2 (KB) | π | k_máx | r | N |
|---|---|---|---|---|---|---|---|---|---|
| 210 | 0.01 | 0.90 | 2.0 | 90 | 425 | 0.004 | 5 | 0 | 14 |

## Cómo ejecutar

Abrir el notebook en Jupyter o Colab con los CSV en la misma carpeta y correr **Run All**. Toda la aleatoriedad sale de `np.random.default_rng(S)`.

## Avance

El checklist con lo hecho y lo pendiente está en los [Issues](../../issues) (uno por ítem, con etiquetas por parte). El resumen general está en el issue fijado **"Checklist general del proyecto"**.
