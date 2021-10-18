# regextutorial

## REGEX TUTORIAL

A regular expression (abbreviated regex or regexp; also known as rational expression) is a character sequence that provides a search pattern. String-searching algorithms typically use such patterns for string "find" or "find and replace" operations, as well as input validation.

# Summary

This is a tutorial that breaks down and describes each part of a regular expression, or regex, to show how it works.

I will be using the below expression to demonstrate how the regex works and how we can build up search algorithms. 

# Expression :

/\(?(\d{3})\)?[ -]?(\d{3})[ -]?(\d{4})/g

# Regex Components :

https://www.fon.hum.uva.nl/praat/manual/Regular_expressions_1__Special_characters.html

 https://regexr.com


## Table of Contents

- [Quantifiers](#Quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#Character-classes)
- [Capturing](#capturing)
- [Flags](#Flags)


### Quantifiers :* + ? and {} : 

{n} Matches a number with n number of digits
eg. {3}matches a number with 3 digits
{4} matches a number with 4 digits

### OR Operator [] : 
Here [ -]? it means either space or a hypen - 

### Capturing Group : () : Groups multiple token together and creates a capture group for extracting a substring or using a backreference. 


### Character Classes : \d \w\s and :
\d matches a single character that is a digit

### Flags : g m i :
Flags can be used to elaborate the scope of search algortihm . 
g is used for global . The search doesnot get completed after its first match , it still goes upto the end. 



## Author
 This tutorial was created by Japjeet . I am an optimistic learner and will be applying my full potential and skills in creating web applications. 

 https://github.com/japjeet1975

