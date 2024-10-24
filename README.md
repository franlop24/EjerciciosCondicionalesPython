# Condicionales con Python

## Condicional simple

```
if expresion_booleana:
    instrucciones
```

## Condicional If Else

```
if expresion_booleana:
    instrucciones
else:
    instrucciones
```

## Condicional Múltiple
```
if expresion_booleana:
    instrucciones
elif expresion_booleana:
    instrucciones
elif expresion_booleana:
    instrucciones
else:
    instrucciones
```

## Condicionales Anidados
```
if expresion_booleana:
    if expresion_booleana:
        instrucciones
    elif expresion_booleana:
        instrucciones
    else:
        instrucciones
else:
    instrucciones
```

## Expresiones Booleanas con Operadores Booleanos

#### AND
```
True  and True  -> True
True  and False -> False
False and True  -> False
False and False -> False
```
#### OR
```
True  or True  -> True
True  or False -> True
False or True  -> True
False or False -> False
```

#### NOT
```
not True      -> False
not False     -> True
```

Se utiliza cuando queremos evaluar 2 o más expresiones, por ejemplo:
- Verificar si un número está en un rango de 0 a 10
-- El numero debe ser mayor o igual que 0 y menor o igual que 10
```
num >= 0 and num <= 10
```
- Validar un usuario y contraseña
-- Si el usuario coincide y la contraseña coincide entoces deja acceder
```
user == user and password == password
```
- validar que: los niños y adultos mayores no pagan pasaje
-- Si la edad es menor a 10 o es mayor a 65
```
edad < 10 or edad > 65
```