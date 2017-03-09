# Panda
Panda is a library providing data structure and data analysis tools for Python.
From text file load data constructed with rows and columns.


iPython / Jupiter Notebook

#ipython
import pandas
df1 = pandas.DatFrame([[2,4,6],[10,20,30]])
print df1

df1 = pandas.DatFrame([[2,4,6],[10,20,30]], columns=["Price","Age","Value"],index=["First","Second"])


df2=pandas.DataFrame([{"Name":"John"},{"Name":"Jack"}])
print df2

print (type(df1))

dir(df1)
#Mean method
df1.mean()

df1.mean().mean()

df1.Price

#JUPYTER
In terminal - jupyter Notebook

enter command - Type commands for the same session
ctrl + enter - to get the output by ending the session
alt + enter - to start new session of commands
shift + enter - to print current commands and start new session
esc + d d - to go back to previous session
