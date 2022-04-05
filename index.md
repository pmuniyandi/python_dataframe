## DataFrame Working Example

This page will explain specific dataframe concept using step by step code. Also having youtube link to explain, so that text, code and video will explain the same concept.

### Different way to create Panda Series

Introduction to [dataframe](https://youtu.be/k9osBqPlO6g "Dataframe Introduction")

Important Parameters of Series data, index, dtype,name, copy Setting/passing data. Setting/changing index. Setting/changing data type. Setting/changing name. How to use copy attribute Creating Series using numpy array Creating Series using dictionary

```
import pandas as pd
marks = [70,75,90,69,87]
idx = ["s1","s2","s3","s4","s5"]
ps = pd.Series(marks,index=idx,dtype="float", copy = False)
print(ps["s2"],ps[1])
print(ps.dtype)
print(ps)

print(ps.gt(10))
ps.describe
```
