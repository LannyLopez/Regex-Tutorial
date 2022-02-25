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
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/
### Anchors
Anchors are the symbols at the beginning or end of the statement which start with ^ and end with $ these nest the rest of the the operations 
### Quantifiers
Quantifier matches the preceding element one or more times, but as few times as possible. For example in this statement there are quite a few such as https? meaning that the URL must have http

### Character Classes
The character classes found in this statement are \d and \w 

The \d searches for any digit 0-9 
The \w searches for any word  

### Grouping and Capturing
In this Component there Is Four groupings https?:\/\/ is the first grouping we find  [\da-z\.-] being the second [a-z\.]{2,6} being the Third [\/\w \.-]* and this being the final
### Bracket Expressions
Bracket expressions are anything being said within brackets [] for example 
[\da-z\.-]
### Greedy and Lazy Match
Greedy matches will start with + where as Lazy matches will start with ? for example this component has a lazy match in the http grouping at the beginning indicated by ?


## Author

This gist was written by Lanny Lopez [My GitHub](github.com/LannyLopez)
