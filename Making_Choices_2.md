```python
import numpy
```


```python
data = numpy.loadtxt(fname='inflammation-01.csv', delimiter=',')


```


```python
max_inflammation_0 = numpy.amax(data, axis=0)[0]
```


```python
max_inflammation_20 = numpy.amax(data, axis = 0)[20]

if max_inflammation_0 == 0 and max_inflammation_20 == 20:
    print('saspictious looking maxima!')
```

    saspictious looking maxima!



```python
max_inflammation_20 = numpy.amax(data, axis = 0)[20]

if max_inflammation_0 == 0 and max_inflammation_20 == 20:
    print('saspictious looking maxima!')

elif numpy.sum(numpy.amin(data, axis = 0)) == 0:
    print('minima add up to zero!')
    
else:
    print('seems OK!')
```

    saspictious looking maxima!



```python
data = numpy.loadtxt(fname = 'inflammation-03.csv', delimiter=',')

max_inflammation_0 = numpy.amax(data, axis = 0)[0]

max_inflammation_20 = numpy.amax(data, axis = 0)[20]

if max_inflammation_0 == 0 and max_inflammation_20 == 20:
    print('suspicious looking maxima!')
elif numpy.sum(numpy.amin(data, axis=0)) == 0:
    print('minima add up to zero! -> Healthy participant alert!')
else:
    print('Seems okay')
```

    minima add up to zero! -> Healthy participant alert!



```python

```
