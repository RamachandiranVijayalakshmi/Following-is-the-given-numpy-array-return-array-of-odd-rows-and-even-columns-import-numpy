## Following-is-the-given-numpy-array-return-array-of-odd-rows-and-even-columns-import-numpy
## Sample code to check the details 
```sh
import numpy

sampleArray = numpy.array([[3 ,6, 9, 12], [15 ,18, 21, 24], 
[27 ,30, 33, 36], [39 ,42, 45, 48], [51 ,54, 57, 60]]) 
print("Printing Input Array")
print(sampleArray)

print("\n Printing array of odd rows and even columns")
newArray = sampleArray[::2, 1::2]
print(newArray)
```
## Example Output
Printing Input Array
[[ 3  6  9 12]
 [15 18 21 24]
 [27 30 33 36]
 [39 42 45 48]
 [51 54 57 60]]

 Printing array of odd rows and even columns
[[ 6 12]
 [30 36]
 [54 60]]


