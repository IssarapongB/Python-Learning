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


