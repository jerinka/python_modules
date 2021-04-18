# Module imports

$tree
.
|-- main.py
|-- A
|   |-- mainA.py
|   |-- module1
|   |   |-- script1.py
|   |   `-- script11.py
|   `-- module2
|       `-- script1.py

3 directories, 5 files

# sys path append

```
import sys
sys.path.append('A')

from A.mainA import hello

hello()
```


