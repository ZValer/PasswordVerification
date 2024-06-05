# PasswordVerification

# E4 Demonstration of a Programming Paradigm

## Description
Choose a useful problem to solve using a specific programming paradigm (App, ICPC, script).
Explain the context of the problem and why it is useful. 

In our everyday we use passwords. 

## Model of the Solution

### Automaton 
##### Generating the Automaton that recognizes the language.

A deterministic finite automaton (DFA) is a quintuple (K, Σ, q<sub>0</sub>, F, δ) where:  
- K: Finite number of states  
- Σ: Finite characters of the alphabet   
- q<sub>0</sub> ∈ K: Single designated start state
- F: Final state
- δ is a function form K x Σ to K which are the transitions (Nakayama, n.d.).


This was the automaton used to represent a secure password...   

- The nodes in the graph are states which are letters, numbers or symbols.
- The symbol in the arches represent the actions taken or the next character.
- The first line represents the start.
- The double circle represents an acceptable or correct state.
- States with no double circle are not acceptable states


### Regular Expression
##### Generating a regular expression that is equivalent to the language.

The regular expression can be thought of as the algebraic description of a regular language and, as mentioned before, any language that can be described in an automaton can also be written as a regular expression. Therefore, the represented automaton is equivalent to the following regular expression:

...  
Breaking down the expression we have the following:  

...   

## Implementation
Implement your solution in a language that supports the programming paradigm.

### Automaton
For my implementation of a lexical analysis, I followed the automaton as can be seen in ...

> [!TIP]
> To test it in a terminal you need to go the folder with the file, write "swipl" and then "["x"].".
> 
>Then put the input in the format "check(password).", for example "check([0,0,1,1,2,2]).", and the program should return "yes" if the string is accepted or "no" if the string is not part of the language.

Some examples of inputs and outputs are:
- check([0,0,1,1,2,2]).
no
...


### Regular expression
For the second implementation, I followed the regular expression as can be seen "x.py" fyle. 

The regex implementation can be found in the x.py file. To run the program in the terminal follow the instructions below:

> [!TIP]
> To test it in a terminal you need to go the folder with the file, write "python regex.py".
> 
>Then put the input the string you want to check, for example "001122", and the program should return "Accepted" if the string follows the regular expression or "Rejected" if the string doesn't.
> 

## Tests

To show that the implemented model works as intended and correctly solves the problem a set of documented tests are shown. 

### DFA

The file "automatonTests.pl" contains test cases for the DFA. 
> [!TIP]
>To test it in a terminal you need to go the folder with the file, write "swipl" and then "["x"].".   

image

### Regular Expression

The file "test_regex.py" contains test cases for the Regular Expression.
> [!TIP]
>To test it in a terminal you need to go the folder with the file, write "pyhton test_regex.py".

image   

## Analysis 

### DFA
The complexity of my model is in general O(n). 
.... 

### Regular Expression
The complexity of my model is in general O(n). 

...

## Conclusion

...   


## References
Thakur, S. (2023). What Is The Difference Between DFA And NFA?. Unstop. Retrieved from: https://unstop.com/blog/difference-between-dfa-and-nfa

NTU. (2018). Regular Expressions (Regex).  NTU. Retrieved from: https://www3.ntu.edu.sg/home/ehchua/programming/howto/Regexe.html 

Freitag, P. (2008). Regex Cheat Sheet. Petefreitag. Retrieved from: https://www.petefreitag.com/cheatsheets/regex/ 

Nakayama, M. (n. d.). CS 341: Foundations of CS II. Computer Science Department. New Jersey Institute of Technology. Retrieved from: https://web.njit.edu/~marvin/cs341/notes/chap01-handout4.pdf 
