```python
farenheit_val = 99
celcius_val = ((farenheit_val - 32) *(5/9))

print(celcius_val)
```

    37.22222222222222



```python
farenheit_val2 = 43
celcius_val2 = ((farenheit_val2 - 32) *(5/9))

print(celcius_val2)
```

    6.111111111111112



```python
def explicit_fahr_to_celcius(temp):
    # Assign the converted value to a variable
    converted = ((temp - 32) * (5/9))
    # return the values of the new variable
    return converted
```


```python
def fahr_to_celcius(temp):
    # return converted values more efficiently using the return function without creating
    # a new variable. this code does the same thing as the previous funciton but it is more
    # explicit in explaining how the return command works
    return ((temp - 32) * (5/9))
```


```python
fahr_to_celcius(32)
```




    0.0




```python
explicit_fahr_to_celcius(32)
```




    0.0




```python
print('freezing point of water:', fahr_to_celcius(32), 'C')
print('boiling point of water:', fahr_to_celcius(212), 'C')
```

    freezing point of water: 0.0 C
    boiling point of water: 100.0 C



```python
def celcius_to_kelvin(temp_c):
    return temp_c + 273.15

print('freezing point of water in kelvin:', celcius_to_kelvin(0.))
```

    freezing point of water in kelvin: 273.15



```python
def fahr_to_kelvin(temp_f):
    temp_c = fahr_to_celcius(temp_f)
    temp_k = celcius_to_kelvin(temp_c)
    return temp_k

print('boiling point of water in kelvin:', fahr_to_kelvin(212.0))
```

    boiling point of water in kelvin: 373.15



```python

```


```python
temp_kelvin = fahr_to_kelvin(212.0)
print('temperature in kelvin was:', temp_kelvin)
```

    temperature in kelvin was: 373.15



```python
temp_kelvin
```




    373.15




```python
def print_temperatures():
    print('temperatures in farenheit was:', temp_fahr)
    print('temperature in kelvin was:', temp_kelvin)
    
temp_fahr = 212.0
temp_kelvin = fahr_to_kelvin(temp_fahr)

print_temperatures()
```

    temperatures in farenheit was: 212.0
    temperature in kelvin was: 373.15



```python

```
