# Figuras Geométricas
## Autor
Yoha Pool Ricse
## Cambios realizados para cumplir con PEP 8 y pylint

- Se renombró el archivo de FiguraGeometrica.py a figura_geometrica.py (formato snake_case)
- Se agregó docstring al módulo y a todas las clases
- Se eliminaron pass y ... innecesarios en métodos abstractos, reemplazándolos por raise NotImplementedError(...)
- Se corrigieron los espacios en blanco y la alineación en las asignaciones y argumentos
- Se dejó una sola línea en blanco al final del archivo
- Se eliminaron variables temporales innecesarias dentro de los métodos calcular_area
- Se añadieron directivas # pylint: disable=too-few-public-methods a clases simples con un único método público
- Se conservaron nombres de constantes en mayúsculas para variables globales
## Dependencias
Este proyecto no requiere librerías externas. Solo utiliza módulos estándar de Python (abc).


```bash
python figura_geometrica.py
