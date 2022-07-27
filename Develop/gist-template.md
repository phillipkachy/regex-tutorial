# Matching a URL - Regex

A "Regex" (regular expression) is defined as a sequence of characters that defines a search pattern 

## Summary

Matching a URL: /^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/
URL' will include the following components 

- http or https
    A URL must start with http or https in the address. 
- :// 
    will then follow either the hypertext transfer protocol. 
- www
    The synonym of www is "world wide web", comes after the http or https. 

- The next element in the url address is a "subdomain" which may vary in length between (2 and 256) characters. 
- File path 
- .com, .org, .edu etc...
    The final component will be the top level domain such as a .com, .org or .edu

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components
To capture "reports" or "reports.html" in any path, begin your match after the last /, and capture word characters and .
### Anchors
Anchors are used to filter the begining and end of a URL.
### Quantifiers
Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found.
### OR Operator
symbolizes the OR or 'Alternate' operator which essentially performs a either match whatever's to the left or right of the '|'.
### Character Classes
The main character classes to consider in the above expression include the \d character class which looks for any digit, and the \w character class that looks for any alphanumeric character.
### Flags
/ delimits regular expressions and are commonly seen at the beginning and/or at the end and at times after anchors too. This is used to identify search criteria outside of the Flags to help mark the expression as global (g), insensitive (i) or multi-line (m).

### Grouping and Capturing
As patterns within a string search begin to get more complicated, Grouping Constructs becomes essential to partition regex using ( ) in order to match only a portion of the string at a time.
### Bracket Expressions
[ ] helps identify which portions of the expression can be any or all of the characters within the Bracket Expression
### Greedy and Lazy Match
- The lazy mode of quantifiers is an opposite to the greedy mode. It means: “repeat minimal number of times”.
We can enable it by putting a question mark '?' after the quantifier, so that it becomes *? or +? or even ?? for '?'.
### Boundaries
Bondaries are defines by the \b symbol at the begening and /b at the end.
### Back-references
When matching characters in a group more than once, or for a repeat of a string, back-references may be used. 
### Look-ahead and Look-behind
To find occuring patterns that are next to each other look-ahead and look-behind can be used. 
## Author
Phillip Kachy

Github:

https://github.com/phillipkachy