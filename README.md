# python-cuil
This code provide functions to calcule a cuil from genre and dni. *(Cuil is Codigo Unico de Identificacion Laboral - Argentina)*


## Example

```python
from python-cuil.cuil import Person
c = Person(31449202, Person.MALE)
print(c.cuil())
>>> 20-31449202-2
```
