# Git the Jist of RegEx
Matching a Hex Value

## Summary
/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

#? = Match # Y/N(0 or 1)
() Captures the group of items
within the first group
[a-f0-9] this matches a charachter within the rages of a-f and 0-9 and is case sensitive the {6} that follows says to match 6 of the previous items
| means OR so it is either match what is before it OR after it.
[a-f0-9] this matches a charachter within the rages of a-f and 0-9 and is case sensitive the {3} that follows says to match 3 of the previous items

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

### Anchors

^$

### Quantifiers

{,num}
{num, num}
{num,}
{num}
? = 0 OR 1
+ = 1 or More, 0 is NG
### OR Operator

 | = Left OR Right of the pipe
### Character Classes

Pre - defined Character Classes
When the letter is capatalized it means the oppiste(NOT)
\s = whitespace
\d = digit
\w = word
\b = word boundary i.e 

### Flags

Flags usually come at the end of the pattern:

/[abc]/i = these letters exactly upper or lowercase
i = Ignore Casing
g = global
s = Dot All
m = Multi Line
y = Sticky
u = Unicode

### Grouping and Capturing

() = When wrao RegEx tokens in () they are treated as a group.

### Bracket Expressions

[] = Used to make a list of Acceptable or Unacceptable tokens.

### Greedy and Lazy Match

{}? = Lazy Match it matches the preceding character as few as possible

### Boundaries

### Back-references

### Look-ahead and Look-behind

?= Positive Lookahead
?! Negitive Lookahead
?<= Positive Lookbehind
?<! Nrgitive Lookbehind

## Author

Author: Zasen.01
Git Hub: https://github.com/zasen01

