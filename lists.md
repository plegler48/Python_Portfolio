```python
odds = [1, 3, 5, 7]
print('odds are:', odds)
```

    odds are: [1, 3, 5, 7]



```python
print('first element:', odds[0])
print('last element:', odds[3])
print('"-1" element', odds[-1])
```

    first element: 1
    last element: 7
    "-1" element 7



```python
names = ['curie', 'darwing', 'turing'] # Typo in darwin's name

print('names is originally:', names)

names[1] = 'Darwin' # Correct the name

print('final value of names:', names)
```

    names is originally: ['curie', 'darwing', 'turing']
    final value of names: ['curie', 'Darwin', 'turing']



```python
#name = 'Darwin'
#name[0] = 'd'
```


```python
odds.append(11)
print('odds after adding a value:', odds)
```

    odds after adding a value: [1, 3, 5, 7, 11]



```python
removed_element = odds.pop(0)
print('odds after removng the first element:', odds)
print('removed element:', removed_element)
```

    odds after removng the first element: []
    removed element: 11



```python
odds.reverse()
print('odds after reversing:', odds)
```

    odds after reversing: []



```python
odds = [3, 5, 7]
primes = odds
primes.append(2)
print('primes:', primes)
print('odds:', odds)
```

    primes: [3, 5, 7, 2]
    odds: [3, 5, 7, 2]



```python
odds = [3, 5, 7]
primes = list(odds)
primes.append(2)
print('primes:', primes)
print('odds:', odds)
```

    primes: [3, 5, 7, 2]
    odds: [3, 5, 7]



```python
binomial_name = "Drosophila melanogaster"
group = binomial_name[0:10]
print('group:', group)

species = binomial_name[11:23]
print('species:', species)

chromosomes = ['X', 'Y', '2', '3', '4']
autosomes = chromosomes[2:5]
print('autosomes:', autosomes)

last = chromosomes[-1]
print('last:', last)
```

    group: Drosophila
    species: melanogaster
    autosomes: ['2', '3', '4']
    last: 4



```python
date = 'Monday 4 January 2023'
day = date[0:6]
print('using 0 to begin range:', day)
day = date[:6]
print('omitting beginning index:', day)
```

    using 0 to begin range: Monday
    omitting beginning index: Monday



```python
months = ['jan', 'feb', 'mar', 'apr', 'may', 'jun', 'jul', 'aug', 'sep', 'oct', 'nov', 'dec']
sond = months[8:12]
print('with known last position:', sond)

sond = months[8:len(months)]
print('using len() to get last entry:', sond)

sond = months[8:]
print('omitting ending index:', sond)
```

    with known last position: ['sep', 'oct', 'nov', 'dec']
    using len() to get last entry: ['sep', 'oct', 'nov', 'dec']
    omitting ending index: ['sep', 'oct', 'nov', 'dec']



```python

```
