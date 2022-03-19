import pandas
import numpy

a = {'a1' : [1,2,3],'b1' : [4,5,6],'c1' : [7,8,9]}
b = {'a1' : [1,2,3],'b1' : [4,5,6],'c1' : [7,8,9]}
c = {'a1' : [1,2,3],'b1' : [4,5,6],'c1' : [7,8,9]}

df1 = pd.DataFrame(a)
df2 = pd.DataFrame(b)
df3 = pd.DataFrame(c)

print(df1)
print(df2)
print(df3)
