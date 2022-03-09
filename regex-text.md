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

Example: ^ and $
The ^ starts a string that includes the characters after it, while the dollar sign signifies the end of a string. Think of them as quotation marks.

### Quantifiers

Example: * (matchers pattern 0 or more times), + (matches the pattern one or mote times)
Quantifers limit the string your regex finds, like minimum and maximum length of the string. Inherently greedy but can be made lazy with a ? after it.

### OR Operator
Example: |
The OR operator used like so (a|b|c) as opposed to (abc) will match with abc, acb, or other combination of the letters instead of a more exact match.

### Character Classes
Example: . (matches any character except the newline (\n)) \d (matches any arabic numeral) \w (matches any alphanumeric character from basic Latin)
Character classes determine a selection of characters, any one will lead to a match with an input string

### Flags
Example: g (globabl search) i (case insensitive search)
Flags are put at the end of regex and define additional functions or limits of the regex.

### Grouping and Capturing
Example: (abc):(xyz)
Allows you to group a portion oof regex with (), making each section a subexpression. Subexpressions look for an exact match as a default. Capturing will capture the matched character sequences for possible re-use while non-capturing groups do not. 

### Bracket Expressions

example: []
Whatever is inside a set of brackets [] are the characters we want to use. For example [xyz] will find a string inclucing x or y or z. You can also use a hypen like [x-z] which will include all the characters between.

### Greedy and Lazy Match
Greedy match tries to match as many times as possible, and a lazy match will try as few times as possible.

### Boundaries
Example: \b
It is an anchor that allows you to search for whole words like so: \bword\b this way you can search for a specific word with your regex.

### Back-references
Example: ([abc])\1
Allows the regex to match the same text that was matched with the first group. You can also increase the number to chose which capturing group you want it to match. Like ([abc])([de])\2 will looke for the 2nd capturing group.

### Look-ahead and Look-behind
Example: d(?=r) (matches a d only if followed by an r, the r will not be part of the regex match)
Example: (?<=r)d (matches a d only if the r came first, the r will not be part of the regex match)


## Author
Mac Glenn, coding student
https://github.com/MacFGlenn

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
