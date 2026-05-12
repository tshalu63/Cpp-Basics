# 🚀 C++ Basics - Complete Beginner Guide

<div align="center">

![C++](https://img.shields.io/badge/C++-Programming-blue?style=for-the-badge)
![Level](https://img.shields.io/badge/Level-Beginner_To_Advanced-success?style=for-the-badge)
![DSA](https://img.shields.io/badge/Useful_For-DSA-orange?style=for-the-badge)

</div>

---

# 📖 What is C++?

C++ is a:

```text
General Purpose Programming Language
```

developed by:

```text
Bjarne Stroustrup
```

It is an extension of:

```text
C Language
```

with additional features like:

✅ Object Oriented Programming  
✅ STL (Standard Template Library)  
✅ Fast Execution  
✅ Memory Management  
✅ High Performance  

---

# 🚀 Why Learn C++?

C++ is widely used in:

✅ DSA & Competitive Programming  
✅ Game Development  
✅ Operating Systems  
✅ Embedded Systems  
✅ Software Development  
✅ High Performance Applications  

---

# 📌 Features of C++

| Feature | Description |
|---|---|
| Fast | Very high performance |
| OOP | Supports classes & objects |
| Portable | Runs on multiple platforms |
| STL | Ready-made data structures |
| Dynamic Memory | Memory management support |
| Multi-Paradigm | Procedural + OOP |

---

# 🏗️ Structure of C++ Program

```cpp
#include <iostream>
using namespace std;

int main()
{
    cout << "Hello World";

    return 0;
}
```

---

# 📚 Explanation of Each Part

| Part | Meaning |
|---|---|
| #include<iostream> | Header file |
| using namespace std | Use standard namespace |
| int main() | Starting point of program |
| cout | Used for output |
| return 0 | Program ends successfully |

---

# 🎯 First Program

```cpp
#include <iostream>
using namespace std;

int main()
{
    cout << "Welcome to C++";

    return 0;
}
```

---

# ✅ Output

```text
Welcome to C++
```

---

# 📌 Input and Output in C++

---

# ✅ Output using cout

```cpp
#include <iostream>
using namespace std;

int main()
{
    cout << "Hello";

    return 0;
}
```

---

# ✅ Input using cin

```cpp
#include <iostream>
using namespace std;

int main()
{
    int age;

    cin >> age;

    cout << age;

    return 0;
}
```

---

# 📌 Variables in C++

Variables store data.

---

# 🏗️ Syntax

```cpp
dataType variableName;
```

---

# ✅ Example

```cpp
int age = 20;
float price = 99.5;
char grade = 'A';
```

---

# 📚 Rules for Variables

✅ Can contain letters, digits, _  
✅ Cannot start with number  
✅ No spaces allowed  
✅ Keywords not allowed  

---

# 📌 Data Types in C++

| Data Type | Example |
|---|---|
| int | 10 |
| float | 3.14 |
| double | 99.999 |
| char | 'A' |
| bool | true |
| string | "Shalu" |

---

# 📌 Integer Data Type

```cpp
int num = 100;
```

Stores whole numbers.

---

# 📌 Float Data Type

```cpp
float price = 99.5;
```

Stores decimal values.

---

# 📌 Double Data Type

```cpp
double pi = 3.141592;
```

More precision than float.

---

# 📌 Character Data Type

```cpp
char grade = 'A';
```

Stores single character.

---

# 📌 Boolean Data Type

```cpp
bool isPassed = true;
```

Stores:

```text
true / false
```

---

# 📌 String Data Type

```cpp
string name = "Shalu";
```

Stores text.

---

# 📚 Operators in C++

---

# 🔹 Arithmetic Operators

| Operator | Meaning |
|---|---|
| + | Addition |
| - | Subtraction |
| * | Multiplication |
| / | Division |
| % | Modulus |

---

# ✅ Example

```cpp
int a = 10;
int b = 5;

cout << a + b << endl;
cout << a - b << endl;
cout << a * b << endl;
cout << a / b << endl;
```

---

# 🔹 Relational Operators

| Operator | Meaning |
|---|---|
| == | Equal |
| != | Not Equal |
| > | Greater |
| < | Smaller |
| >= | Greater Equal |
| <= | Smaller Equal |

---

# 🔹 Logical Operators

| Operator | Meaning |
|---|---|
| && | AND |
| \|\| | OR |
| ! | NOT |

---

# 🔹 Assignment Operators

| Operator | Meaning |
|---|---|
| = | Assign |
| += | Add Assign |
| -= | Subtract Assign |
| *= | Multiply Assign |

---

# 📌 Conditional Statements

---

# ✅ if Statement

```cpp
#include <iostream>
using namespace std;

int main()
{
    int age = 20;

    if(age >= 18)
    {
        cout << "Adult";
    }

    return 0;
}
```

---

# ✅ if-else Statement

```cpp
if(num % 2 == 0)
{
    cout << "Even";
}
else
{
    cout << "Odd";
}
```

---

# ✅ else-if Ladder

```cpp
int marks = 85;

if(marks >= 90)
{
    cout << "A";
}
else if(marks >= 70)
{
    cout << "B";
}
else
{
    cout << "C";
}
```

---

# 📌 Switch Statement

```cpp
int day = 2;

switch(day)
{
    case 1:
        cout << "Monday";
        break;

    case 2:
        cout << "Tuesday";
        break;

    default:
        cout << "Invalid";
}
```

---

# 🔁 Loops in C++

Loops repeat code.

---

# ✅ for Loop

```cpp
for(int i=1; i<=5; i++)
{
    cout << i << endl;
}
```

---

# ✅ while Loop

```cpp
int i = 1;

while(i <= 5)
{
    cout << i << endl;
    i++;
}
```

---

# ✅ do-while Loop

```cpp
int i = 1;

do
{
    cout << i << endl;
    i++;
}
while(i <= 5);
```

---

# 📌 Break and Continue

---

# ✅ break

Stops loop completely.

```cpp
for(int i=1; i<=10; i++)
{
    if(i == 5)
        break;

    cout << i << endl;
}
```

---

# ✅ continue

Skips current iteration.

```cpp
for(int i=1; i<=5; i++)
{
    if(i == 3)
        continue;

    cout << i << endl;
}
```

---

# 📌 Functions in C++

Functions are reusable blocks of code.

---

# 🏗️ Syntax

```cpp
returnType functionName()
{
    // code
}
```

---

# ✅ Example

```cpp
#include <iostream>
using namespace std;

void greet()
{
    cout << "Hello";
}

int main()
{
    greet();

    return 0;
}
```

---

# 📌 Function with Parameters

```cpp
void add(int a, int b)
{
    cout << a + b;
}
```

---

# 📌 Function with Return Value

```cpp
int square(int n)
{
    return n * n;
}
```

---

# 📌 Arrays in C++

Arrays store multiple values.

---

# 🏗️ Syntax

```cpp
int arr[5];
```

---

# ✅ Example

```cpp
int arr[5] = {1,2,3,4,5};

cout << arr[0];
```

---

# 🔁 Traversing Array

```cpp
for(int i=0; i<5; i++)
{
    cout << arr[i] << endl;
}
```

---

# 📌 Strings in C++

---

# ✅ String Example

```cpp
string name = "Shalu";

cout << name;
```

---

# ✅ Input Full Line

```cpp
getline(cin, name);
```

---

# 📌 Pointers in C++

Pointers store memory addresses.

---

# ✅ Example

```cpp
int x = 10;

int *ptr = &x;

cout << ptr << endl;
cout << *ptr << endl;
```

---

# 📚 Pointer Symbols

| Symbol | Meaning |
|---|---|
| & | Address of variable |
| * | Value at address |

---

# 📌 Dynamic Memory Allocation

---

# ✅ new Operator

```cpp
int *ptr = new int;
```

---

# ✅ delete Operator

```cpp
delete ptr;
```

---

# 📌 Object Oriented Programming (OOP)

---

# 🚀 Class and Object

---

# ✅ Class Example

```cpp
class Student
{
    public:

    int id;
    string name;
};
```

---

# ✅ Object Example

```cpp
Student s1;

s1.id = 101;
s1.name = "Shalu";
```

---

# 📌 Constructor

Constructor initializes object.

---

# ✅ Example

```cpp
class Student
{
    public:

    Student()
    {
        cout << "Constructor Called";
    }
};
```

---

# 📌 Destructor

Destructor destroys object.

---

# ✅ Example

```cpp
~Student()
{
    cout << "Destroyed";
}
```

---

# 📌 Inheritance

Allows one class to acquire another class properties.

---

# ✅ Example

```cpp
class Animal
{
    public:

    void sound()
    {
        cout << "Animal Sound";
    }
};

class Dog : public Animal
{
};
```

---

# 📌 Polymorphism

Same function behaves differently.

---

# ✅ Function Overloading

```cpp
class Math
{
    public:

    int add(int a, int b)
    {
        return a+b;
    }

    int add(int a, int b, int c)
    {
        return a+b+c;
    }
};
```

---

# 📌 STL in C++

STL = Standard Template Library

Provides ready-made:

✅ Data Structures  
✅ Algorithms  
✅ Iterators  

---

# 📚 Important STL Containers

| Container | Use |
|---|---|
| vector | Dynamic Array |
| stack | LIFO |
| queue | FIFO |
| map | Key-Value |
| set | Unique Data |

---

# 📌 Vector Example

```cpp
#include <vector>

vector<int> v;

v.push_back(10);
v.push_back(20);

cout << v[0];
```

---

# 📌 Stack Example

```cpp
#include <stack>

stack<int> s;

s.push(10);
s.push(20);

cout << s.top();
```

---

# 📌 Queue Example

```cpp
#include <queue>

queue<int> q;

q.push(10);
q.push(20);

cout << q.front();
```

---

# 📌 Map Example

```cpp
#include <map>

map<int, string> mp;

mp[1] = "Shalu";

cout << mp[1];
```

---

# 📌 Set Example

```cpp
#include <set>

set<int> s;

s.insert(10);
s.insert(20);
```

---

# 📌 Exception Handling

---

# ✅ try-catch Example

```cpp
try
{
    int a = 10/0;
}
catch(...)
{
    cout << "Error";
}
```

---

# 📌 File Handling

---

# ✅ Writing File

```cpp
#include <fstream>

ofstream file("test.txt");

file << "Hello";
```

---

# ✅ Reading File

```cpp
ifstream file("test.txt");

string data;

file >> data;
```

---

# 📌 Important Keywords

| Keyword | Meaning |
|---|---|
| class | Create class |
| public | Access modifier |
| private | Hidden data |
| virtual | Runtime polymorphism |
| this | Current object |
| new | Dynamic memory |
| delete | Free memory |

---

# 📌 Time Complexity Basics

| Operation | Complexity |
|---|---|
| Array Access | O(1) |
| Linear Search | O(n) |
| Binary Search | O(log n) |
| Nested Loops | O(n²) |

---

# 🎯 Best Practices

✅ Use meaningful variable names  
✅ Write clean code  
✅ Avoid global variables  
✅ Use functions properly  
✅ Learn STL deeply  
✅ Practice coding daily  

---

# 🌍 Real Life Applications of C++

---

# 🎮 Game Development

Used in:

- Unreal Engine
- AAA Games

---

# 🖥️ Operating Systems

Used in:

- Windows
- Linux Components

---

# 🚗 Embedded Systems

Used in:

- Robotics
- Cars
- IoT Devices

---

# 🌐 High Performance Systems

Used in:

- Browsers
- Databases
- Servers

---

# 📌 Conclusion

C++ is one of the most powerful programming languages.

It helps in:

✅ DSA  
✅ Competitive Programming  
✅ Software Development  
✅ System Programming  
✅ Interview Preparation  

Mastering C++ builds strong logic and problem-solving skills.

---

# ⭐ Recommended Next Topics

1. Arrays
2. Strings
3. Pointers
4. Recursion
5. STL
6. OOP
7. DSA
8. Competitive Programming                                         NB

---

# ⭐ Support

If you found this repository useful, give it a ⭐ on GitHub!

---
