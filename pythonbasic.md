```python
# say hello
print("Hello World")
print("Hello\nWorld")
```

    Hello World
    Hello
    World
    


```python
print('Hello World')
```

    Hello World
    


```python
print(Hello World)
```


      File "<ipython-input-3-10cb182148e3>", line 1
        print(Hello World)
                    ^
    SyntaxError: invalid syntax
    



```python
type int(1.0)
```




    float




```python
type int(1.0)
```


      File "<ipython-input-5-a1b9289e4ddd>", line 1
        type int(1.0)
             ^
    SyntaxError: invalid syntax
    



```python
int(1.0)
```




    1




```python
bool(1)
```




    True




```python
import sys
print(sys.version)
```

    3.8.5 (default, Sep  4 2020, 00:03:40) [MSC v.1916 32 bit (Intel)]
    


```python
# variables
min=160
min

hrs= min//60
hrs
```




    2




```python
print("hi")

print(r"hi\hello")
```

    hi
    hi\hello
    


```python
A= "god is good"
B=A.upper()
B
```




    'GOD IS GOOD'




```python
B=A.replace('god','Jesus')
B
```




    'Jesus is good'




```python
A.find('is')
```




    4




```python
"uppercase".upper()
```




    'UPPERCASE'




```python
Numbers="0123456"
Numbers[::2]
```




    '0246'




```python
Numbers[::3]
```




    '036'




```python
"0123456".find('1')
```




    1




```python
# indexing
Name= "Michael Jackson"
Name
```




    'Michael Jackson'




```python
# Print the element on index 6 in the string

print(Name[6])
```

    l
    


```python
# Print the element on index 0 in the string

print(Name[0])
```

    M
    


```python
# Print the last element in the string

print(Name[-1])
```

    n
    


```python
# Find the length of string

len("Michael Jackson")
```




    15




```python
# Take the slice on variable name with only index 0 to index 3

Name[0:4]
```




    'Mich'




```python
# Take the slice on variable name with only index 8 to index 11

Name[8:12]
```




    'Jack'




```python
# Take the slice on variable name with only index -4 to index -1

Name[-3:]
```




    'son'




```python
# New line escape sequence

print(" Michael Jackson \n is the best" )
```

     Michael Jackson 
     is the best
    


```python
# Tab escape sequence

print(" Michael Jackson \t is the best" )
```

     Michael Jackson 	 is the best
    


```python
# Include back slash in string

print(" Michael Jackson \\ is the best" )
```

     Michael Jackson \ is the best
    


```python
# r will tell python that string will be display as raw string

print(r" Michael Jackson \ is the best" )
```

     Michael Jackson \ is the best
    


```python
# Convert all the characters in string to upper case

a = "Thriller is the sixth studio album"
print("before upper:", a)
b = a.upper()
print("After upper:", b)
```

    before upper: Thriller is the sixth studio album
    After upper: THRILLER IS THE SIXTH STUDIO ALBUM
    


```python
# Replace the old substring with the new target substring is the segment has been found in the string

a = "Michael Jackson is the best"
b = a.replace('Michael', 'Janet')
b
```




    'Janet Jackson is the best'




```python
# Find the substring in the string. Only the index of the first elment of substring in string will be the output

name = "Michael Jackson"
name.find('el')
```




    5




```python
#Consider the variable g, and find the first index of the sub-string snow
# Write your code below and press Shift+Enter to execute

g = "Mary had a little lamb Little lamb, little lamb Mary had a little lamb \
Its fleece was white as snow And everywhere that Mary went Mary went, Mary went \
Everywhere that Mary went The lamb was sure to go"
g.find("snow")
```




    95




```python
# replace mary with bob
g.replace('Mary','Bob')
```




    'Bob had a little lamb Little lamb, little lamb Bob had a little lamb Its fleece was white as snow And everywhere that Bob went Bob went, Bob went Everywhere that Bob went The lamb was sure to go'




```python

```
