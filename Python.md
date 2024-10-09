- Code not to learn
- 1:4
- Level 1 : Basic formula based
- Level 2 : conditions + loops
- Level 3 : Data structures + Strings
- Level 4 : Logic Building on real life Problems
- Level 5 : Online coding Platform (Hacker Rank,Leetcode)

- **Python is Hybrid (nor compiler nor interpretor) does both**
Python is older language than java 

**Why Python is good?**
1. Simple Syntax
2. Lose Syntax
    - options: "Hello"
                'Hello'
                    "'Hello'"
                        """Hello"""
                        eol ; or without it
3. Dynamic Casting 
    
    give data ---> data type will ne taken
    
    a=10 ---int
    
    a=12.3 ---float
    
    a="amar" ---str
    
    a=True ---bool T and F capital

    want to check data type of anything use **type()**

    # Primitive types in python
        int,float,str,bool,complex

    # Data structures build in (primitive structure)
        list,set,tuple,dict

4. Multipurpose 
    
    --- script/oops/procedure fucntion based

5. All new technologies direactly / indireactly uses python 
    
    DS/ML/AI

# How many generations of programming language
  1 Generation - Machine language
  
  2 Generation - Assemble language
  
  3 Generation - High level language
  
  4 Generation - SQL 
  
  5 Generation - NLP/AI  

Unicode(Universal code) is 16 bits 

# Character Set
- ASCII ---> C/C++ ---- 8 bit : english only
- UNICODE ---> Universal Code: 16 bits (Java , Python)
          ---> 24 language on scripts

IDLE - Integrated development learning environment
IDE - Integrated development environment

# Conditional Statement

- if 

one option

moslty within loop to print right answer

- if else

2 options 

mostly at end of the print result

- if elif-elif-else

2+ 

at most one block from many to execute

# If
```python 
if condition:
  #if block
  #
  #
# out of if
```

# IF ELSE IF
```python
#+ve,-ve
no=int(input("Enter a number:"))
if no>0:
    print(f"{no} is +ve")
elif no<0:#else if
    print(f"{no} is -ve")
else:
    print(no,"is zero")

```

# IF ELSE 
```python
#+ve,-ve
no=int(input("Enter a number:"))
if no>0:
    print("in if")
    print(f"{no} is +ve")
    print("bye")
else:#else has no condition
    print("in if 2")
    print(f"{no} is -ve")
    print("bye 2")
```

# Loop

start : init value

step: +k -k

condition: stop

---------------------------------------------------------------------------------------------------

# Day 2

# For Loop

```python
range(start,end,step)
default values : if not given then taken 
  start:0
  step:+1
  end:on python we will stop at n-1 
```
step should be int

+ve = -1 end

-ve = +1 end

Slow because it works on list in background so it takes more memory

# Anonymous Varaible

```python 
for _ in range(1,10):
  print("x")
```

Basically used for pattern printing

```python 
for i in range(1,4):
  for j in range(1,4):
    print(f"i:{i} , j:{j}") 
```
for each pass of external loop internal loop runs n times

# Flag concept

flag set ---> true flag=reset --->False

set then if fail reset

reset if found/match/got set

check if number is prime or not

# Data Structure (Primitive DS)

way of storing data in such a way that it is effective , easy to access as per need and application

- Stack: LIFO

- Tree: Hierarchy view , store data , sort , search large data

- Queue: FIFO

- Linked List: Dynamic Linear Structure, Consider to be most powerful as can implement all data structure

- Graph: max used today , Google maps are graph , biometrics are graph


<h2>primitive to python</h2> 

set,list,tuple,dictionary


coder: maximum used is list for its dynamic nature
set for filteration
dict for mapping key to data/data set

python: used tuple for security

<h2>Common in all 4 </h2> 

- hetrogeneous

- created with symbols
  
  [] list
  
  () tuple
  
  {1} set

  {1:"value"} dictionary

  <br>
 
<h2> also construtors/cast types available</h2>
  
  list()
  
  set()

  tuple()

  dict()

<h1>List</h1>
<br>

- hetrogeneous
- dynamic: can grow/shrink over runtime
- indexed: +ve and -ve
- duplicate allowed
- printable
- iterable
- +can concate
- *repeats


<h3>Every data structure is shellow copy<h3>

# SET
<br>

- {} -----> use set() for creating empty set

- hetrogeneous
- dynamic: can grow/shrink over runtime
- custom indexed hence cannot be accessed via index     stores on its own way
- duplicate allowed
- printable
- iterable

# DAY 3

# String

String is still inmutable in python

# Functions

#pass by value and ref

    #all primitive types
    #changes only seen by and in function only

#call by value and ref

    #all data strucutres
    #changes done in function seen by every one,every where

# OOPS (Object Oriented Programming)

What is OOPS?

<h2>It is thinking process where we follow bottom to top approach of thinking and devlopment</h2>

In industry we start by knowing what we need as o/p and work ourself on process and i/p

implementation of oops happening over 

class 
-------------------------------------------------------------------------
virtual identity 

giving framework of idea

has properties 

has operations to access/set/reset properties



object
=================================================================================
physical identity (he/she/it)

implementation of framework of idea

has values of properties

has methods to access/set/reset value of properties 


# PILLARS use in implementation

<h2>Encapsulation:</h2>

process of combining data+function to operate on data 

Advantages
- ease of operation
- Better control on access

Example
- Laptop + bag + antivirus + Windows + Extra Things 

<h2>Abstraction:</h2>

hide unwanted details and giving simple access/simpler view of data 

Advantages
- Simpler view/needed view as per user ease
- hide complexity using visibilities/ access specifiers

Example
- Life
- Car starting
- any menu of pizza

Anything starting with double underscore( __ str __ ) is a system method

<h2>Inheritance:</h2>

ability to create something new by taking properties of pre existing 

new = old ref + new things ===> you

Use
- faster development due to reuse
- standards 
- enhancement(improve with time/adaption)

single 

multilevel

multiple

hierarchical

hybrid

keyword word use in python for inheritance 

()

```python
class<sub_class>(superclass):
    #code
```

Strong private chodke bakki saari cheeze inherit karte hai

Why java not supporting multiple inheritance? 

because ambiguity can not be be handled/resolved 

ambiguity : multiple parents have same method it is not possible tp define whos method will be / should be inherited

python we could handle this by FCFT (First come first taken Mehthod)

take from 1st reject from all next 

Which inheritance is not supported by java ? it done in pyhton by FCFT method


<h1>Over-ride</h1>

when child class rewrites parent method it rejects inheritnace/rejects inherited method and create own

reason:

adapt to changes wrt time and development


# Visualization 

data presented in terms of graphs

text takes time but visuals will not 

example: signs on road

humans adapts to image more than image more than text

- .plot : gives line plot

# NumPy

will be used for doing matrix based manipulation it could support 1D , 2D , 3D arrays 

# RegeX

used in validation text data extraction/text scrapping 

# Package

Folder with classes, functions precoded to be used/called 

- +ve: package makes it simple to share and resuse
- manage code with right package

<h1>python:</h1>

project

--------------------> resources

--------------------> dependencies

--------------------> precoded data/ref

main script called ---- other things are linked in it

packages:

1. create folder of a name:
2. in this folder __ init __ .py act as ref of activation can be blank
3. add needed file with .py
4. import package 

   import package as 


# How to study python 

Basics 30+
- operators 
- loops 
- conditions

Mid level 50+
- Data Structures 
- String 

LeetCode/CC/HR ....


# JOB 

1. Custom Resume to apply 

    basic text+chatgpt(jd)

    read thid jd and modify resume givenn to suit 

    prompt : Tell me what points to improve , why

2. prepare as per need / jd / company / 

    website: glassdoor , ambitionbox