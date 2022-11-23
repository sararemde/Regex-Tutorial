# Regex Tutorial

A regular expression is a sequence of characters that specifies a search pattern in text. Usually, patterns are used by string-searching algorithms for "find" or "find and replace" operation on string, or for input validation.

## Summary

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

This regex example represents matching an email. Every component and symbol has a responsiblity to make sure that the user enters the email in the correct format.

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

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/


### Anchors

The characters we use to express anchors are ^ and $. They are used to match a position before, after, or between characters. 


They can be used to "anchor" the regex match at a certain position. 

### Quantifiers

Quantifiers are characters that have strings limits. For example in the example above it the + and {} would be limiting quantifiers. 

### OR Operator


### Character Classes

Character classes are used to distinguish specific kinds of characters from a certain set. 

### Flags

Regular expressions may have flags that affect the search. There are only 8 of them in JavaScript:
- i
- g
- m
- s
- u
- y

### Grouping and Capturing

By placing part of a regular expression insied round brackets or parentheses, you can group that part of the regular expression together. This allows you to apply a quantifier to the entire group or to restrict alternation to part of the regex.

In thhis example it includes the following groupd: ([a-z)-9_.-]+). The + sign means we match at least one or more of any characters in the square brackets. a-z is talking about the lowercase letters from a-z, 0-9 includes the numbers from 0 to 9. 

### Bracket Expressions

Anything inside a set of square brackets ([]) represents a range of characters that we want to match. We can write these expressions to include all the characters we wnat to match. For example our expresssion has: ([a-z0-9_.-]+), ([\da-z.-]+), and ([a-z.]{2,6})

### Greedy and Lazy Match



### Boundaries



### Back-references



### Look-ahead and Look-behind



## Author



A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
