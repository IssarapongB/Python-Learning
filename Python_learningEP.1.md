# Python Lerning Conclusion EP 1

#### Python Getting Started

Install Python

python --version

pyhton -V

#### Comment Method / basic print 

#This is a comment

print("Hello, World!")


#### Creating Variables (การกำหนดตัวแปล)
x = 5
y = "John"
print(x)
print(y)

#### Python - Variable Names (กฏการกำหนดชื่อตัวแปร)
1. ชื่อตัวแปรต้องขึ้นต้นด้วยตัวอักษรหรือขีดล่าง
2. ชื่อตัวแปรไม่สามารถขึ้นต้นด้วยตัวเลขได้
3. ชื่อตัวแปรมีได้เฉพาะอักขระตัวอักษรและตัวเลขและขีดล่าง (Az, 0-9 และ _ )
4. ชื่อตัวแปรต้องตรงตามตัวพิมพ์ใหญ่-เล็ก
5. ชื่อตัวแปรต้องไม่ใช่คีย์เวิร์ดPython ใดๆ

#### Many Values to Multiple Variables การกำหนดตัวแปร

##### One Value to Multiple Variables
###### 1. x, y, z = "Orange", "Banana", "Cherry"

print(x)

print(y)

print(z)

##### 2. x = y = z = "Orange"

print(x)

print(y)

print(z)

##### Unpack a Collection : list Variables
fruits = ["apple", "banana", "cherry"]
x, y, z = fruits

print(x)

print(y)

print(z)


##### Global Variables

  def myfunc():
  
    global x
  
    x = "fantastic"

  myfunc()
  
    print("Python is " + x)


##### Built-in Data Types

ในการเขียนโปรแกรม ชนิดข้อมูลถือเป็นแนวคิดที่สำคัญ

ตัวแปรสามารถจัดเก็บข้อมูลได้หลายประเภท และประเภทที่แตกต่างกันก็สามารถทำสิ่งต่าง ๆ กันได้

Python มีประเภทข้อมูลในตัวตามค่าเริ่มต้นในหมวดหมู่เหล่านี้:

1. Text Type:	str (การเก็บตัวแปรข้อความ) -> x = "Hello World"
2. Numeric Types:	int (จำนวนนับ) -> x = 20 , float (ทศนิยม) -> x = 20.5 , complex (จำนวนเชิงซ้อน)  -> x = 1j
3. Sequence Types:	list -> x = ["apple", "banana", "cherry"]	 , tuple -> x = ("apple", "banana", "cherry")	 , range  -> x = range(6)
4. Mapping Type:	dict -> x = {"name" : "John", "age" : 36}
5. Set Types:	set -> x = {"apple", "banana", "cherry"} , frozenset -> x = frozenset({"apple", "banana", "cherry"})
6. Boolean Type:	bool -> x = True
7. Binary Types:	bytes -> x = b"Hello" , bytearray -> x = bytearray(5) , memoryview -> x = memoryview(bytes(5))
8. None Type:	NoneType -> x = None

 Ex. show type 
 
   x = 5
 
  print(type(x))

##### Python - Slicing Strings

Get the characters from position 2 to position 5 (not included):

b = "Hello, World!"

print(b[2:5])

output : llo

###### Slice To the End

b = "Hello, World!"

print(b[2:])

output : llo, World!

###### Negative Indexing

b = "Hello, World!"

print(b[-5:-2])

output : orl

###### Python - Modify Strings

###### Upper Case

a = "Hello, World!"

print(a.upper())

output : HELLO, WORLD!

###### Lower Case

a = "Hello, World!"

print(a.lower())

output : hello, world!

###### Remove Whitespace

a = " Hello, World! "

print(a.strip()) # returns "Hello, World!"

###### Python - String Concatenation

a = "Hello"

b = "World"

c = a + b

print(c)

output : HelloWorld

###### To add a space between them, add a " ":

a = "Hello"

b = "World"

c = a + " " + b

print(c)

output : Hello World

###### Python - Format - Strings

Example

age = 36

txt = "My name is John, I am " + age

print(txt)

###### Use the format() method to insert numbers into strings:

Example 1

age = 36

txt = "My name is John, and I am {}"

print(txt.format(age))

Example 2

quantity = 3

itemno = 567

price = 49.95

myorder = "I want {} pieces of item {} for {} dollars."

print(myorder.format(quantity, itemno, price))

output : I want 3 pieces of item 567 for 49.95 dollars.

Example 3

quantity = 3

itemno = 567

price = 49.95

myorder = "I want to pay {2} dollars for {0} pieces of item {1}."

print(myorder.format(quantity, itemno, price))

output : I want to pay 49.95 dollars for 3 pieces of item 567

###### Python - Escape Characters

txt = "We are the so-called \"Vikings\" from the north."

Escape Characters

Code	Result

\'	Single Quote

\\	Backslash

\n	New Line

\r	Carriage Return

\t	Tab

\b	Backspace

\f	Form Feed

\ooo	Octal value

\xhh	Hex value


