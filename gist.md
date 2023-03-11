 Regex-Tutorial
Regex is a sequence of characters that form a pattern. Regex does not require any code. A major downside to regex is that it looks extremely confusing. Regex is extremely useful for searching for numbers or information stored in patterns like phone numbers. For example, searching for a phone number by hand would be difficult, but regex allows you to search for things based on their pattern. 

## Summary
This will be my expression of choosing for the tutorial
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
During the start of a regex expression the '/' is used to read the expression, the '^' is used as the start point, and the '$' near the end is used as an ending point. These are anchors that define the start and beginning of an expression. The entire string needs to match the ID address pattern.
### Quantifiers
Quantifier's main job is determining whether there is only one match or multiple. Sometimes quantifiers are filled by letters as placeholders, but mostly '*' '?' '+' are used as quantifiers.
### OR Operator
When attempting to match distinct patterns, the character "|" is utilized as an OR operator. It is used in our regex to match the range of values for each IP address section.
### Character Classes
The character class "[0-9]" corresponds to any single digit. This class is used to match each number in an IP address.
### Flags
A regex can have a flag as an optional parameter that changes the way it searches. A flag modifies a regular expression's default searching behavior. It does a regex search distinctively. An individual lowercase alphabetic character is used to represent a flag.
### Grouping and Capturing
Parentheses with the symbol "()" are used to group patterns. To organize the various IP address parts, we employ them in our regex. The non-capturing group '?:' groups patterns without capturing the text that matches them.
### Bracket Expressions
The '[]' brackets match any single character in the specified range. For each IP address segment, we utilize this to compare the range of values.
### Greedy and Lazy Match
Regex matching is by nature greedy, meaning it seeks out as many matches as it can. By using the quantifier "?" to make the matching lazy, we can reduce the number of matches.
### Boundaries
To make sure that the IP address is not a component of a longer term, we employ the '\b' boundary in our regex.
### Back-references
Backreferences match the same text that was previously matched by a capturing group. Consider a scenario in which you wish to match the text in between two opening and closing HTML tags. We can reuse the tag name from the opening tag for the closing tag by placing it into a back reference. How to do it is as follows: '([A-Z][A-Z0-9]*)b>]*>.*?/1>.'
### Look ahead and Look-behind
Look-ahead and look-behind assertions are only used to match text based on the sequence. We are not currently using look-ahead or look-behind assertions in our regex.
## Author

MaxWFell(https://github.com/MaxWFell).
