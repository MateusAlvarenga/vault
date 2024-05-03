```python

import numpy as np  
vetor = np. array ([1,2,3,4,5])
print(vetor)
```


```python

import numpy as np 
vetor = np.array ([1,2,3]) 
print(np.linalg.norm(vetor))

```


```python

import numpy as np 
vetor1 = np.array([1,2,3]) 
vetor2 = np.array([3,4,5]) 
print(vetor2 + vetor1)
print(vetor2 - vetor1)

print(3 * vetor2)
print("----")
print(np.array([[-2,4],[-9,9]]))

print("----")

print(np.array([[-2,4],[-9,9]]).transpose())

```


```python

import numpy as np 
import math 

b = np.array([1,1,4]) 

a = np.array([-1,2,2]) 

produto_escalar = np.dot(a,b) 
angulo_radiano = math.acos(produto_escalar/(np.linalg.norm(a)*np.linalg-norm(b))) angulo_grau = c*180/np.pi 
print('O ângulo entre os vetores, em radiano, é:', angulo_radiano) 
print('O ângulo entre os vetores, em grau, é:' , angulo_grau)

```


![[Untitled 2024-04-27 16.22.23.excalidraw]]