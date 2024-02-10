## Key-value pair

```yaml
name: Krishna
1: "I'm software Engineer"
```
## List

```yaml
- Apple
- mango
- Banana
- banana
```
or
```yaml
cities: [Bangalore, Delhi, kolkata]
```
### `---` to seperate the documentes and `...` to end the documentes

### String and variable
```yaml
name: Krishna # variable
fruits: "apple" # String
job: 'swe' #String
```
### Multiline String
```yaml
cities: |
Delhi
kolkata
```
### Single line in multiple line
```yaml
message: >
    thsi will
    all be in
    one single line
```

### specify data type
```yaml
# Integer
zero: !!int 0
positiveNum: !!int 50
negativeNum: !!int -60
binaryNum: !!int 011

#Float
marks: !!float 53.44
infinity: !!float .inf
not a num: .nan
boolean: !!bool false

# Exponential number
exponent: 6.22ES56

# String
string: !!str "hi yaml"

# Null
surname: !!null Null # or null NULL ~
~: this is a null key

# Dates and time
date: !!timestamp 2002-01-02
no Time zone: 2012-12-15T02:59:43
India Time: 2012-12-15T02:59:43 +5:30

```

### Nested Sequence
```yaml
-
 - apple
 - mangoe
-
 - marks
 - roll num
 - date

```

### Nested Mapping
```yaml
name: Krishna Kumar
roll:
    age: 24
    job: swe
```
### Reusing  properties
