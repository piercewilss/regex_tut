# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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
The caret ^ is an anchor that matches the first position before the first character in the string. Similarly, $ is an anchor that matches the last character in the string.

### Quantifiers
Quantifiers specify how many instances of a character, group, or character class must be in the input for a match to be found.
piercewilson1@live.com
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
### OR Operator
You can use the | operator (logical OR) to match characters or expression of either the left or right of the | operator.
### Character Classes
In the context of regular expressions, a character class is a set of characters enclosed within square brackets. It specifies the characters that will successfully match a single character from a given input string.
### Flags
A regular expression consists of a pattern and optional flags: g , i , m , u , s , y .


### Grouping and Capturing
Groups group multiple patterns as a whole, and capturing groups provide extra submatch information when using a regular expression pattern to match against a string.
### Bracket Expressions
A bracket expression (an expression enclosed in square brackets, "[]" ) is an RE that shall match a specific set of single characters, and may match a specific set of multi-character collating elements, based on the non-empty set of list expressions contained in the bracket expression.


### Greedy and Lazy Match
'Greedy' means match longest possible string.

'Lazy' means match shortest possible string.
### Boundaries
Boundary markers such as ^ and $ allow you to anchor the regex pattern to the beginning and end of the line.
### Back-references
A backreference in a regular expression identifies a previously matched group and looks for exactly the same text again. A simple example of the use of backreferences is when you wish to look for adjacent, repeated words in some text. The first part of the match could use a pattern that extracts a single word
### Look-ahead and Look-behind
Lookahead and lookbehind, collectively called “lookaround” are zero-length assertions.
Lookaround actually matches characters but then gives up the match, returning only the result: match or no match. 
## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
