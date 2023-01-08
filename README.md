# Librería para imprimir tablas

## Instalación

Utilice el siguiente comando en la terminal para la instalación de la librería.

`pip install ERlib`

## Uso
Para imprimir su tabla simplemente tienes que crear tu tabla y mandar a llamar a la función `printTable(Tabla)`, puedes colocar un título a la tabla el cual si lo colocas se imprimirá primero el título y después la tabla.

## Parámetros

Se utlizan dos parámetros:


## Ejemplo de uso:
### Código
```python
from ERlib import printTable

TituloDeLaTabla = "Los equipos con más Champions League"

Tabla = [
    ["Posición", "Equipo", "Títulos"],
    ["1°", "Real Madrid Club de Fútbol", 14],
    ["2°", "Associazione Calcio Milán", 7],
    ["3°", "Bayern de Múnich", 6],
    ["4°", "Liverpool Fútbol Club", 6],
    ["5°", "Fútbol Club Barcelona", 5]
]

printTable(Tabla, TituloDeLaTabla)
```
### Salida:

![](https://github.com/ERwiin21MP/printTable/blob/main/salida.png)
