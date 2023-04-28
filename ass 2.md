```python
# 1. solution 
marks = int(input("enter a number"))
if marks>90:
    print("you will be grade A batch")
elif marks>80 and marks<=90:
    print("you will be grade B batch")
elif marks>=60 and marks<=90:
    print("you will be grade C batch")
else:
    print("you will be grade D batch")
    
```

    enter a number 70


    you will be grade C batch



```python
# 2.solution
tax = int(input("enter cost prices Rs"))
if tax>=100000:
    a = tax*15/100
    print("tax in 15%\ntax prices this amount= ",a,"RS")
elif tax>50000 and tax<100000:
    b = tax*10/100
    print("tax in 10%\n tax prices this amount = ",b,"RS")
else:
    c = tax*5/100
    print("tax in 5%\n tax prices this amount = ",c,"RS")
```

    enter cost prices Rs 60000


    tax in 10%
     tax prices this amount =  6000.0 RS



```python
# 3. solution
print("choses the city and finf monuments\n city name- DELHI,AGRA,JAIPUR")
int(input("enter a city name following chart"))
l1 = ["delhi" ,"agra","jaipur"]
for i in l1:
    if  i =="delhi":
        print("red fort")
    elif i =="agra":
        print("taj mahal")
    elif i =="jaipur":
        print("taj mahal")
        
        
```

    choses the city and finf monuments
     city name- DELHI,AGRA,JAIPUR


    enter a city name following chart DELHI,AGRA,JAIPUR



    ---------------------------------------------------------------------------

    ValueError                                Traceback (most recent call last)

    Cell In[4], line 3
          1 # 3. solution
          2 print("choses the city and finf monuments\n city name- DELHI,AGRA,JAIPUR")
    ----> 3 int(input("enter a city name following chart"))
          4 l1 = ["delhi" ,"agra","jaipur"]
          5 for i in l1:


    ValueError: invalid literal for int() with base 10: 'DELHI,AGRA,JAIPUR'



```python
# 4. solution 
n =int(input("enter a number"))
if n%3 ==0:
    print("divided by 3")
else:
    print("not divided by 3")
    
```

    enter a number 3


    divided by 3



```python
# 5.solution 
''' python while loop is used to execute a block of statements repeatedly until a given condition 
    is satisfied and when the condition becomes false , the line immediately after loop in the program
    is executed'''
     n = int(input("enter a number"))
     i = 1 
    while i<=n:
         print(i)
    i = i+2
```


      File <tokenize>:7
        while i<=n:
        ^
    IndentationError: unindent does not match any outer indentation level




```python
# 6. solution 
# sum n natural number 
n = int(input("enter a number"))
i = 1
5 == 0
while i<=n:
    5 == 5+i
    i+= 1
    print("sum of n number",s)
    #
```


```python
# 7. solution 
i = 10
while i10:
    print(i)
i = i-l
```


```python


```
