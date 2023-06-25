# Regex Tutorial

## Introduction

Welcome to the Regex Tutorial! In this tutorial, we will explore a specific regular expression (regex) pattern that allows us to match a combination of a word and digits. We will break down each component of the regex pattern and explain its functionality. By the end of this tutorial, you will have a clear understanding of how to use this regex pattern to search for specific patterns in strings.

## Summary

In this tutorial, we will be focusing on a regex pattern that matches a string consisting of a word followed by a space and then a series of digits. The regex pattern is as follows:



\```regex
^(?<word>[A-Za-z]+)\s(?<digits>\d+)$
\```


We will discuss each component of the regex pattern and understand how it contributes to the overall matching process.

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

Anchors in regex are symbols that allow us to match specific positions within a string. In our regex pattern, we utilize two anchors:

- `^` - The caret symbol anchors the match at the start of the line.
- `$` - The dollar sign anchors the match at the end of the line.

### Quantifiers

Quantifiers in regex specify the number of times a character or group should occur. In our pattern, we don't explicitly use quantifiers, but the `+` quantifier is implied in the character class for the word part.

### OR Operator

The OR operator in regex allows us to specify multiple alternatives for a pattern. Our pattern does not include the OR operator.

### Character Classes

Character classes in regex define a set of characters that can match at a specific position in a string. In our pattern, we employ character classes to specify the allowed characters for the word part:

- `[A-Za-z]` - This character class matches any alphabetical character, both uppercase and lowercase.

### Flags

Flags in regex modify the behavior of the pattern matching. In our pattern, we do not use any flags.

### Grouping and Capturing

Grouping and capturing allow us to isolate parts of a regex match. In our pattern, we utilize parentheses to create capture groups:

- `([A-Za-z]+)` - This capture group captures one or more alphabetical characters (the word part).
- `\s` - The `\s` matches a single whitespace character (the space between the word and the digits).
- `(\d+)` - This capture group captures one or more digits (the digit part).

### Bracket Expressions

Bracket expressions in regex allow us to define a set of characters enclosed within square brackets. Our pattern does not include bracket expressions.

### Greedy and Lazy Match

Greedy and lazy matching in regex specify how much of the input should be matched. Our pattern does not explicitly demonstrate greedy or lazy matching.

### Boundaries

Boundaries in regex allow us to match specific positions in a string, such as the beginning or end of a word. Our pattern does not include boundaries.

### Back-references

Back-references in regex allow us to refer to previously captured groups within the pattern. Our pattern does not utilize back-references.

### Look-ahead and Look-behind

Look-ahead and look-behind assertions in regex allow us to specify conditions that must be met ahead or behind the current position. Our pattern does not involve look-ahead or look-behind.

## Author

This tutorial was written by Bobby Atwood, a web development student. You can find more of his work on [GitHub](https://github.com/batwood99).

[Go to Author's GitHub Profile](https://github.com/batwood99)

By understanding each component of the regex pattern, you now have the knowledge to use it effectively. Experiment with different input strings and observe how the regex pattern matches or extracts the desired parts.

