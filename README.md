# ACD_Assignment1
# Automata and Compiler Design — Assignment 1  

This project implements basic concepts of Automata Theory using Python.  

## 📌 Project Overview  

The assignment includes:  

DFA implementation  
NFA implementation  
NFA to DFA conversion  
Testing of DFA, NFA, and converted DFA  

The automata recognize binary strings containing the substring 01.  

## 1. DFA  

The DFA accepts strings containing 01.  

States: {A, B, C, D}  
Alphabet: {0, 1}  
Start State: A  
Accept States: {C, D}  

Examples  
001 → ✅ Accepted  
0101 → ✅ Accepted  
111 → ❌ Rejected  

## 2. NFA  

The NFA also accepts binary strings containing 01.  

States: {q0, q1, q2}  
Alphabet: {0, 1}  
Start State: q0  
Accept State: q2  


Examples  
01 → ✅ Accepted  
001 → ✅ Accepted  
111 → ❌ Rejected  

## 3. NFA to DFA Conversion  

The NFA is converted into an equivalent DFA using the Subset Construction Method.  

Each DFA state represents a set of NFA states.  

Example  
{q0, q1}  


The converted DFA is tested to verify that it produces the expected results.  

📊 Results  
DFA — 001 → ✅ Accepted  
DFA — 111 → ❌ Rejected  
DFA — 0101 → ✅ Accepted  
NFA — 01 → ✅ Accepted  
NFA — 001 → ✅ Accepted  
NFA — 111 → ❌ Rejected  
Converted DFA — 001 → ✅ Accepted  
Converted DFA — 111 → ❌ Rejected  

## 🎥 Video Demonstration

[Click here to watch the video](https://drive.google.com/file/d/1MM97J-heZEEiwmEOVQo9Zl7GQ3vrdsNd/view?usp=sharing)


## 📂 Project Structure  
ACD_Assignment1/  
│  
├── ACD_Assignment1.ipynb  
└── README.md  


## ▶️ How to Run  

Open ACD_Assignment1.ipynb in Jupyter Notebook or Google Colab and run the cells.  

## 🛠️ Technologies Used  
Python 3  
Jupyter Notebook  
Google Colab  

## 📚 Concepts  
DFA  
NFA   
NFA to DFA Conversion  

## 👤 Author

M. Tilak Roshan  
Roll No: 25075A7203  
Course: Automata and Compiler Design  
Assignment:1
