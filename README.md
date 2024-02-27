# Regular Expression Tutorial: "Matching a Hex Value"

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
Anchors in a regular expression are indicators that the string is starting or ending. The '^' and '$' in this expression are both anchors which tell the computer where to start looking for the expression and when the expression is over.

>The following hex value statement highlights the anchors in gold:

>/`^`#?([a-f0-9]{6}|[a-f0-9]{3})`$`/
>* **Start:** '^' indicates the string is starting
>* **End:** '$' indicates the end of the string. 

### Quantifiers
Quantifiers set limits on your regex string. They can either indicate things that need to be present in the string or can set a number of characters that a certian part of the string needs to have. The two quantifiers that are present in hex value strings are question marks and curly brackets.

>The following hex value statement highlights the qualtifiers in gold:

>/^#`?`([a-f0-9]`{6}`|[a-f0-9]`{3}`)$/

>* **Question Mark '?':** A question mark means anything that comes before the question mark in the string is optional. In the hex value regex, a # is placed before the ? meaning that the hex color code can have a # in it, or not, either way is fine. 


>* **Curly Brackets '{}':** Curly brackets are quantifiers that indicate how many characters should be in the previous bracket expression (more on those below). In the hex value regex, there is one set of curly brackets with a 6 in it, and one with a 3 in it, meaning the bracket expressions right before the curly brackets must contain 6 or 3 respectively. 

### Grouping Constructs

Parentheses '()'

### Bracket Expressions

Brackets '[]'

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
