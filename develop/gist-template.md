# Module 17 Regex Tutorial

A Regular Expression (Regex), is a sequence of characters used to match patterns in text. 
Regular expressions can extract date from a file such as usernames, emails, phone numbers, and so much more-
from using a specific pattern of code.

## Summary

In this Regex Turtorial, I will be explaining the expression "Matching an Email". This expression could be used to verify an email address is correct. 

Matching an Email: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)


## Regex Components

### Anchors

The ^ anchor indicates the beginning of a string, and the $ anchor indicates the end of a string. 

### Quantifiers

A Quantifier is generally used for indicating the max and min amount of characters that Regex is searching for, setting the limit of the string. One quantifier found in our snippet is {2,6} which will allow a match range of 2-6 characters of the characters [a-z\.]. 

### Character Classes

The character class found in this snippet is \d, which will match a single character that is from 0-9 as well as only match a single digit.

### Grouping and Capturing

The main way to group a section of a Regex is to use parentheses. 

There are three sections in our code snippet:

First: ([a-z0-9_\.-]+) is the email name before the '@domain'

Second: ([\da-z\.-]+) is the name of the email domain.

Third: ([a-z\.]{2,6}) is the last part of an email address (.org, .com. .net, etc.)


### Bracket Expressions

Bracket Expressions set the range of characters to be matched.

### Greedy and Lazy Match
Matches in the email Regex are Greedy Matches. A Lazy Match would try to match as little as possible, whereas a Greedy Match will match as much as possible.

## Author

Tayler Baldwin, University of Richmond Full Stack Development Student. 

GitHub Profile: https://github.com/justmoonflower