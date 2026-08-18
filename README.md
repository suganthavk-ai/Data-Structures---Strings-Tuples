# Data Structures: Strings & Tuples 
The fundamentals of Strings and Tuples in Python, including string operations, slicing, indexing, built-in methods, tuple creation, accessing elements, and basic tuple operations.

## 📌 Overview
This assignment focuses on understanding and implementing Python Strings and Tuples. It covers fundamental operations such as string concatenation, indexing, slicing, built-in string methods, and tuple manipulation. 

## 🎯 Objectives
-	Understand string concatenation using the + operator 
-	Practice string indexing and slicing 
-	Reverse a string using slicing 
-	Extract specific characters and words from a string 
-	Use common string methods 
-	Create and manipulate tuples 
-	Perform tuple concatenation and repetition 
-	Access tuple elements using indexing and slicing 
-	Understand the concept of tuple immutability

## 🧩 Topics Covered

### 1. String Concatenation
The assignment demonstrates how to:
-	Accept user input using input() 
-	Concatenate strings using + 
-	Add additional text to an existing string

Example:

```
name = input("Enter your Name: ")

str1 = "Hello " + name
str3 = ", welcome to Python programming"

result = str1 + str3

print(result)
```

### 2. String Indexing & Slicing
The following operations are performed:

```
result[0]       # First character
result[-1]      # Last character
result[:5]      # First 5 characters
result[-11:]    # Last 11 characters
result[::-1]    # Reverse string
```

The assignment also extracts the word "Python" using index() and slicing.

### 3. String Methods
The assignment uses the following built-in string methods:
| Method | Purpose|
| --------- | ----------- |
| upper() | Converts text to uppercase |
| lower() | Converts text to lowercase |
| capitalize() | Capitalizes the first character | 
| count() | Counts occurrences of a character
| replace() | Replaces specified text |

Example:
```
strM = "Python beginner tutorial"

print(strM.upper())
print(strM.lower())
print(strM.capitalize())
print(strM.count("t"))
print(strM.replace("Python", "Data Analytics"))
```

These methods are specifically included in the assignment requirements.

### 4. Tuples
Two tuples are created:
t1 = (10, 20, 30)
t2 = (40, 50, 60)
The assignment performs:
-	Tuple concatenation 
-	Tuple repetition 
-	Tuple indexing 
-	Tuple slicing 
Example:

```
t_combine = t1 + t2
t_repeat = t_combine * 3
print(t_combine[2])
print(t_combine[:3])
print(t_combine[-3:])
The expected combined tuple is:
(10, 20, 30, 40, 50, 60)
```

### 📚 Skills Practiced

-	String Manipulation 
-	String Indexing 
-	String Slicing 
-	String Methods 
-	User Input & Output 
-	Tuple Creation 
-	Tuple Concatenation 
-	Tuple Repetition 
-	Tuple Indexing 
-	Tuple Slicing 
-	Understanding Immutability

The assignment maps these activities to beginner-level Python data manipulation and data access skills.

## 🛠️ Technologies Used

-	Python 
-	Google Colab / Jupyter Notebook

## 📂 Assignment Structure

Python-Assignment-1/
│
├── Data_Structure_Strings_Tuples.ipynb
└── README.md

## ✅ Learning Outcome

After completing this assignment, I gained practical understanding of Python strings and tuples, including indexing, slicing, string transformation methods, concatenation, repetition, and accessing tuple elements.

## 👩‍💻 Author
Sugantha B
- Aspiring Data Analyst
-	Python | SQL | Power BI | Excel

