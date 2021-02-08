```python
# WAP to accept a word and convert to piglatin from
word = input("Enter the word: ")
for i in range(len(word)):
    if word[i] in 'AEIOU':
        break
lp = word[0:i]
rp = word[i:]
result = rp + lp + "AY"
print(result)

```

    Enter the word: HAPPY
    APPYHAY
    


```python
# WAP to accept a word and convert to piglatin from
word = input ("Enter the word: ")
for i in range (len(word)):
    if word[i] in 'AEIOU':
        break
lp = word[0:i]
rp = word[i:]
result = rp + lp + "AY"
print(result)
```

    Enter the word: ENTER
    ENTERAY
    


```python

```


```python
# print("welcome to currency converter app".title)
dic={"U.S dollar":100,"Euro":100,"Jpy":100}
print("you can convert in following currency:")
for key in dic.keys():
    print("\n"+key.title())
your_value=float(input("enter your amount: "))
currency=input("select your currency you want to convert: ")
if currency=="Us" or currency=="dollar":
    print("you have selected dollar and your total converted amount = "+str(dic["U.S dollar"]*your_value))
elif currency=="euro" or currency=="EURO":
    print("you have selected euro and your total converted amount ="+str(dic["U.S dollar"]*your_value))
elif currency=="Jpy" or  currency=="JPY":
    Print("you have selected jpy and your total converted amount ="+str(dic["U.S dollar"]*your_value))
```

    you can convert in following currency:
    
    U.S Dollar
    
    Euro
    
    Jpy
    enter your amount: 100
    select your currency you want to convert: dollar
    you have selected dollar and your total converted amount = 10000.0
    


```python
# print("welcome to exception(an error)".title)
z=int(6)
y=int('a')
print("Sum of z and y:",z+y)
```


    ---------------------------------------------------------------------------

    ValueError                                Traceback (most recent call last)

    <ipython-input-16-1e69b814f867> in <module>
          1 # print("welcome to exception(an error)".title)
          2 z=int(6)
    ----> 3 y=int('a')
          4 print("Sum of z and y:",z+y)
    

    ValueError: invalid literal for int() with base 10: 'a'



```python
items=[apple,rice,pen,notbook,pencile,pocket,soap,belt,book,sandal,eraser,spoon]
print(len(items))
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    <ipython-input-11-6cb351f5c2cc> in <module>
    ----> 1 items=[apple,rice,pen,notbook,pencile,pocket,soap,belt,book,sandal,eraser,spoon]
          2 print(len(items))
    

    NameError: name 'apple' is not defined



```python
import math
print(math.sqrt(-1.0))
print(sqrt(-1.0))
```


    ---------------------------------------------------------------------------

    ValueError                                Traceback (most recent call last)

    <ipython-input-12-ebc7f9c566b8> in <module>
          1 import math
    ----> 2 print(math.sqrt(-1.0))
          3 print(sqrt(-1.0))
    

    ValueError: math domain error



```python
print(c)
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    <ipython-input-19-1dd5973cae19> in <module>
    ----> 1 print(c)
    

    NameError: name 'c' is not defined



```python
user_str = input('Enter String')
l = user_str.split()
d = {}
for i in l:
    if i not in d.keys():
        d[i] = 0
        d[i] = d[i]+1
        print(d)
```

    Enter Stringthe quick red fox got bored and went home
    {'the': 1}
    {'the': 1, 'quick': 1}
    {'the': 1, 'quick': 1, 'red': 1}
    {'the': 1, 'quick': 1, 'red': 1, 'fox': 1}
    {'the': 1, 'quick': 1, 'red': 1, 'fox': 1, 'got': 1}
    {'the': 1, 'quick': 1, 'red': 1, 'fox': 1, 'got': 1, 'bored': 1}
    {'the': 1, 'quick': 1, 'red': 1, 'fox': 1, 'got': 1, 'bored': 1, 'and': 1}
    {'the': 1, 'quick': 1, 'red': 1, 'fox': 1, 'got': 1, 'bored': 1, 'and': 1, 'went': 1}
    {'the': 1, 'quick': 1, 'red': 1, 'fox': 1, 'got': 1, 'bored': 1, 'and': 1, 'went': 1, 'home': 1}
    


```python
a = [1,1,1,3,5,1,1,2,1,0,1,0,1,2,4,0,1,2,0,2,1,0,1,1,0,0]
b = sorted(a,key = lambda i:a.index(i))
print(b)
```

    [1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 3, 5, 2, 2, 2, 2, 0, 0, 0, 0, 0, 0, 0, 4]
    


```python
user_str = input('Enter String')
l = user_str.split()
d = {}
for i in l:
    if i not in d.keys():
        d[i] = 0
        d[i] = d[i]+1
        print(d)
```

    Enter Stringapple
    {'apple': 1}
    


```python

using System;
using System.Collections.Generic;

namespace ConsoleApp7
{
    class Program
    {
        static void Main(string[] args)
        {
            Dictionary<string, string> names = new Dictionary<string, string>();
            names.Add("1", "Berlioz");
            names.Add("2", "Borodin");
            names.Add("3", "Brian");
            names.Add("4", "Bartok");
            names.Add("5", "Bellini");
            names.Add("6", "Buxtehude");
            names.Add("7", "Bernstein");
            foreach (KeyValuePair<string, string> kv in names)
            {
                Console.WriteLine(kv.Key + "" + kv.Value);

            }









        }

    }
}


















```


      File "<ipython-input-1-b4db6ea4bd45>", line 1
        using System;
              ^
    SyntaxError: invalid syntax
    



```python
using System;

namespace Areaoftriangle3
{
    class Program
    {
        static void Main(string[] args)
        { // program to find the area of a triangle
            double a, b, c;
            double area, s;
            Console.Write("Enter the value of a ===> ");
            a = double.Parse(Console.ReadLine());
            Console.Write("Enter the value of b ===> ");
            b = double.Parse(Console.ReadLine());
            Console.Write("Enter the value of c ===> ");
            c = double.Parse(Console.ReadLine());

            s = (a + b + c) / 2;
            area = Math.Sqrt(s * (s - a) * (s - b) * (s - c));
            Console.WriteLine("The Area of  a retangle is " + area);
            Console.ReadLine();
         
        }
    }
}

```


      File "<ipython-input-2-a5ef8793c0e2>", line 1
        using System;
              ^
    SyntaxError: invalid syntax
    



```python
using System;

namespace old_even
{
    class Program
    {
        static void Main(string[] args)
        {
            int[] arr1 = new int[]
            {
                25,
                47,
                42,
                56,
                32
            };
            int[] arr2 = new int[5];
            int[] arr3 = new int[5];
            int i, j = 0, k = 0;
            for (i=0; i <5; i++)
            {
                if (arr1[i]%2==0)
                {
                    arr2[j] = arr1[i];
                    j++;
                }
                else
              
```


      File "<ipython-input-4-65e114137eb6>", line 1
        using System;
              ^
    SyntaxError: invalid syntax
    



```python
using System;

namespace substring
{
    class Program
    {
        static void Main(string[] args)
        {
            /*
             contains() Method is used to check substring occurs within string.
             If substring is found in string , it returns true else false.
            */
            string s1 = "supercalifragilisticexpialidocious";
            string s2 = "ice";
            Console.WriteLine(s1.Contains(s2));
            Console.ReadLine();
        }
    }
}

```


      File "<ipython-input-5-1fa007157847>", line 1
        using System;
              ^
    SyntaxError: invalid syntax
    



```python
using System;

namespace letteres
{
    class Program
    {
        static void Main(string[] args)
        {
            string txt = "supercalifragilisticexpialidocious";
            Console.WriteLine("The length of given word is" + txt.Length);
        }
    }
}

```


      File "<ipython-input-1-1f9ff7c8ff43>", line 1
        using System;
              ^
    SyntaxError: invalid syntax
    



```python

```
