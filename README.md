# Prime and Composite Number Analyzer

## 📌 Overview
This Python script takes a **range of numbers** as input and classifies each number as **prime** or **composite**. Additionally, it counts the number of prime and composite numbers within the range.

## 🚀 Features
- **Identifies prime numbers** within a given range.
- **Classifies composite numbers** separately.
- **Counts and displays** the number of prime and composite numbers.
- **Optimized prime-checking** using the square root method.

## 🛠 How It Works
1. The user inputs a **lower range** (`a`) and **upper range** (`b`).
2. The program iterates through numbers from `a` to `b` and:
   - Checks if a number is **prime** (using divisibility tests).
   - If not prime and greater than 1, classifies it as **composite**.
   - Keeps a count of prime and composite numbers.
3. Finally, the program **outputs the counts** of both types.

## 🛠 Technologies Used
- **Python 3** (basic loops and conditionals)
- **Mathematical Optimization** (Square root method for prime checking)

## 🔍 Example Usage
```sh
Enter lower range: 10
Enter upper range: 20
Range is (10, 20)
Then the status of each number in the range is:
11 is a prime number
13 is a prime number
17 is a prime number
19 is a prime number
10 is a non-prime or composite number
12 is a non-prime or composite number
14 is a non-prime or composite number
15 is a non-prime or composite number
16 is a non-prime or composite number
18 is a non-prime or composite number
20 is a non-prime or composite number
4 prime and 7 composite numbers in the range
