# python-cuil
This code provide functions to calcule a cuil from sex and dni. *(Cuil is Codigo Unico de Identificacion Laboral)*

## Example

```python
from python-cuil.cuil import Person
c = Person(31449202, Cuil.MALE)
print(c.cuil())
>>> 20-31449202-2
```
