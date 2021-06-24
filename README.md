
## PIP UPDATES

```
pip list --outdated

pip install <package_name> --upgrade

# FOR SPECIFIC USER
pip install <package_name> --upgrade --user

```

## PYTHON EXAMPLES

`Everything is an object in Python`

type:
dir: 

```
>>> import math

>>> type(math)
<class 'module'>

>>> dir(math)

['__doc__', '__file__', '__loader__', '__name__', '__package__', '__spec__', 'acos', 'acosh', 'asin', 'asinh', 'atan', 'atan2', 'atanh', 'ceil', 'comb', 'copysign', 'cos', 'cosh', 'degrees', 'dist', 'e', 'erf', 'erfc', 'exp', 'expm1', 'fabs', 'factorial', 'floor', 'fmod', 'frexp', 'fsum', 'gamma', 'gcd', 'hypot', 'inf', 'isclose', 'isfinite', 'isinf', 'isnan', 'isqrt', 'ldexp', 'lgamma', 'log', 'log10', 'log1p', 'log2', 'modf', 'nan', 'perm', 'pi', 'pow', 'prod', 'radians', 'remainder', 'sin', 'sinh', 'sqrt', 'tan', 'tanh', 'tau', 'trunc']

>>> 

>>> dir(math.cos)

['__call__', '__class__', '__delattr__', '__dir__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__gt__', '__hash__', '__init__', '__init_subclass__', '__le__', '__lt__', '__module__', '__name__', '__ne__', '__new__', '__qualname__', '__reduce__', '__reduce_ex__', '__repr__', '__self__', '__setattr__', '__sizeof__', '__str__', '__subclasshook__', '__text_signature__']

>>> 
```


Raw string: 

```
rawstring = r'Om\Namah:\Shivay'
print(rawstring)
```

while loop:

```
while c !=0:
    print(c)
    c -= 1

while True:
    response = input()
    if int(response) == 1:
        break
```

if loop:

```
if c == 111:
    print("OK")
else:
    if c == 110:
        print("SECOND OK")
    else:
        print("SECOND not OK")

```

FOR loop:

```
x = ["shiv", "hanu"]
for i in x:
    print(i)
```


methods

```
print("Enter your Name: ") 
res = input()
print("Your name is : " + res.capitalize())
```

Bytes:

```
>>> d = b'this is bytes'
>>> d.split()
[b'this', b'is', b'bytes']
>>> d[0]
116

>>> ak = "Hi this is utf8"
>>> data = ak.encode('utf8')
>>> print(data)
b'Hi this is utf8'
>>> 
>>> ak = data.decode('utf8')
>>> print(ak)
Hi this is utf8
```

LIST:

```
LST = [1,2,3]
LST1 = []
```

DICT:

```
DCT: {'KEY1': 'VAL1', 'KEY2':'VAL2'}
DCT2 = {}
```

TUPLE: 

```
>>> t = ("val",1)
>>> type(t)
<class 'tuple'>

```

Importing a function:

1. file with a function
```
import function_example

function_example.method1()

```
2. calling directly a function

```
from function_example import *
method1()

```

function with default argument: Arg with default values must come after those without default values

```
import time
def createbanner(msg, border="-"):
    l = border * len(msg)
    print(l)
    print(msg)
    print(l) 

createbanner("This is Banner")
createbanner(time.ctime(), "$")

```

enumerate 
