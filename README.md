# TEMPERATURAS‑PY

Este proyecto incluye una función en Python para calcular el promedio de temperaturas por ciudad. Está preparado para manejar múltiples ciudades y semanas.

## Contenido

- `temperaturas.py`: contiene la función `calcular_promedio_temperaturas`.

## ¿Cómo usar?

```python
from temperaturas import calcular_promedio_temperaturas

datos = {
    "Quito": [20, 22, 21, 19],
    "Guayaquil": [28, 30, 29, 31],
    "Cuenca": [16, 17, 15, 18]
}

resultado = calcular_promedio_temperaturas(datos)
print(resultado)

Luego haz:
```bash
git add README.md
git commit -m "Agregar README con instrucciones y contexto del proyecto"
git push

