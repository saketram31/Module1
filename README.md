# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```
num=int(input())
if(num%2==0):
      print("Even")
else:
    print("Odd")
```    
## Output
![image](https://github.com/user-attachments/assets/2d1612a7-8a61-4033-88cb-5fcbab407c5c)

## Result
Thus the program has been successfully executed


# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
```
a = (0 == True)
b = (False== False)
c = True + True
d = False + 9
print('a is',a)
print('b is',b)
print('c:',c)
print('d:',d)
```
## Output
![image](https://github.com/user-attachments/assets/ea64d494-b2a2-4b1a-833e-0e561296ecf0)

## Result
Thus, the program as been excuted successfully.

# Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```
v='T'
b='a'
print(v)
print(b)
```

## Output
![438638778-5c5c0e93-5ac7-445c-834d-d26398737ca7](https://github.com/user-attachments/assets/1e47325f-7662-4579-b3c1-2ec2835c552d)

## Result
Thus, the program is executed sucessfully.

# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.


## 💻 Program
```
x=int(input(''))
y=int(input(''))
x=complex(x,y)
print(x)
print(x.real)
print(x.imag)
```
## Output
![438639571-778828b7-6c2b-4a39-9984-6b60a54eb980](https://github.com/user-attachments/assets/31586238-a956-469b-814c-f368cf28d8e2)


## Result
Thus, the program as been executed successfully.

# Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```
men_stepped_on_the_moon=input()
print(men_stepped_on_the_moon)
```
## Output
![438640380-81d01fa2-7ce3-4064-8d86-20faacd67fae](https://github.com/user-attachments/assets/b998caa7-be79-4281-8713-527be2030f2d)

## Result
Thus the program is executed successfully
