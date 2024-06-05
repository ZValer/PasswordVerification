# PasswordVerification

# E4 Demonstration of a Programming Paradigm

## Description
Choose a useful problem to solve using a specific programming paradigm (App, ICPC, script).
Explain the context of the problem and why it is useful. 


We use passwords practically everyday.  From unlocking our phones, entering our email or paying with a card. Passwords work as the principal method of authenticating and protecting us as user, our identities and our sensitive information.

Different apps and systems use different methods of authentication based on the level of security required and user convenience. While apps that handle sensitive information enforce complex passwords, phones for a quick access use shorter passwords, face id or finger prints. Those last two require integration of sensors. However they can´t always be added. 

And for most systems we have to create strong passwords. These are some tips recomended by Microsoft (2024) to do so: 
1. Use at least 12 characters.
2. Use a combination of uppercase letters, lowercase letters, numbers, and symbols.
3. Don't use words that can be found in a dictionary, names, characters, products, or organizations.
4. Make the password significantly different from your previous passwords.
5. Make it easy for you to remember but difficult for others to guess. 

Number 3, 4 and 5 are responsability for the person to implement, as for the first 2, they can be programmed.

## Model of the Solution

### Regular Expression
##### Generating a regular expression that is equivalent to the language.

The regular expression can be thought of as the algebraic description of a regular language and, as mentioned before, any language that can be described in an automaton can also be written as a regular expression. Therefore, the represented automaton is equivalent to the following regular expression:

...  
Breaking down the expression we have the following:  

...   

## Implementation
Implement your solution in a language that supports the programming paradigm.

### Automaton

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

### Regular Expression

The file "test_regex.py" contains test cases for the Regular Expression.
> [!TIP]
>To test it in a terminal you need to go the folder with the file, write "pyhton test_regex.py".

image   

## Analysis 
### Regular Expression
The complexity of my model is in general O(n). 

...

## Conclusion

...   


## References

Microsoft. (2024). Create and use strong passwords. Microsoft. Retrieved from: https://support.microsoft.com/en-us/windows/create-and-use-strong-passwords-c5cebb49-8c53-4f5e-2bc4-fe357ca048eb 

NTU. (2018). Regular Expressions (Regex).  NTU. Retrieved from: https://www3.ntu.edu.sg/home/ehchua/programming/howto/Regexe.html 

Freitag, P. (2008). Regex Cheat Sheet. Petefreitag. Retrieved from: https://www.petefreitag.com/cheatsheets/regex/ 

Nakayama, M. (n. d.). CS 341: Foundations of CS II. Computer Science Department. New Jersey Institute of Technology. Retrieved from: https://web.njit.edu/~marvin/cs341/notes/chap01-handout4.pdf 

