# Regex-Tutorial
Regex is a sequence of characters that form a pettern. Regex does not require any code. A major downside to regex is that it looks extremely confusing. Regex is extremely useful for searching for numbers or information stored in apatterns like phone numbers. For example searching for a phone number by hand would be difficult, but regex allows you to search for things based on their pattern. 

## Summary
This will be my expresssion of choosing for the tutorial
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/



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
During ste start of a regex expression the '/' is used to read the expression, the '^' is used as start point, and the '$' near the end is used as a ending point. These are anchors they define the start and beggining of an expression. The entire string needs to match the ID address pattern.
### Quantifiers
Quantifiers main job is determing wether there is only one match or multiple. Sometimes quantifiers are filled by letters as placeholders, but mostly '*' '?' '+' are used as quantifiers.
### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references
Backreferences match the same text that was previously matched by a capturing group. Consider a scenario in which you wish to match the text in between two opening and closing HTML tags. We can reuse the tag name from the opening tag for the closing tag by placing it into a backreference. How to do it is as follows: '([A-Z][A-Z0-9]*)b>]*>.*?/1>.'
### Look-ahead and Look-behind
Look-ahead and look-behind assertions, are only used to match text based on sequence. We are not currently using look-ahead or look-behind assertions in our regex.

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
