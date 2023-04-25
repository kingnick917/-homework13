# getting to know Regex
What is Regex? is a sequence of characters that defines a specific search pattern.When included in code or search algorithms Such as /^#?([a-f0-9]{6}|[a-f0-9]{3})$/
/^(a-z0-9_\.-]+)@[\da-z\.-]+)\.([a-z\.]{2,6})$/.They are also frequently used to validate input.

## Summary
this is Hex Value
/ = start of regex
^ = begining of string 
# = i don't know 
? = Question Mark
( = associated regex
    [ = set of characters
    a-f = letter
    0-9 = digit
    ]
    {6} =Curly Braces	
    | = Logical OR operator or Pipe
    [= set of characters
    a-f= letter
    0-9= digit
    ]
    {3}=Curly Braces	
    )
    $= end of string
    /=end of regex
 

## Table of Contents

- [Anchors](#anchorss)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors : family of regex but don't match any characters. but that assert something about the string or the matching process

### Quantifiers :matches the preceding element zero or more time but times less as possible

### Grouping Constructs :delineate the subexpressions of a regular expression and capture the substrings of an input string.

### Bracket Expressions :Brackets indicate a set of characters

### Character Classes : set of characters enclosed within square brackets.

### The OR Operator :recognizes range expressions inside a list

### Flags :A flag is denoted using a single lowercase alphabetic character

### Character Escapes :The \ is known as the escape code, which restore the original literal meaning of the following character  * , + , ?

## Author
https://github.com/kingnick917
I am a student going through a coding boot camp that recognize through UC Davis
I am currently 5 weeks away from the end of the boot camp 


