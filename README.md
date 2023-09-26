# REGEX Matching Email Addresses

Regex, short for regular expression, is a powerful tool for matching patterns in text. It is used in many programming languages. In this tutorial, we'll cover how to use regex to match email addresses.

## Summary

We'll be focusing on this email validation regex:

`/^[\w\.-]+@[a-zA-Z\d\.-]+\.[a-zA-Z]{2,6}$/`

Let's explore its key components:

## Table of Contents

- [REGEX Matching Email Addresses](#regex-matching-email-addresses)
  - [Summary](#summary)
  - [Table of Contents](#table-of-contents)
  - [Regex Components](#regex-components)
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
  - [Author](#author)

## Regex Components


----


### Anchors

Anchors in regex are `^` and `$`. They are used to match the beginning and end of a string. In our email regex, we'll use `^` to match the beginning of the string and `$` to match the end of the string.


### Quantifiers

Quantifiers control how many times a pattern must appear in a string. In our email regex, we'll use `*` and `+` to match zero or more and one or more times respectively. We'll also use `{2,6}` to match between 2 and 6 times.

### OR Operator

The OR operator in regex is `|`. It matches either of the patterns in the parentheses. Our email regex doesn't use the OR operator, but it's useful to know about it.

### Character Classes

Character classes, indicated by `[]`, are used to match a specific set of characters. In our email regex, we'll use `[a-zA-Z]` to match any letter. We'll also use `[0-9]` to match any digit.

### Flags

Flags are used to modify the behavior of regex. In our email regex, we'll use `i` to make it case insensitive.

### Grouping and Capturing

Parentheses `()` are used to group parts of a pattern. They also capture matched text. 

### Bracket Expressions

Bracket expressions `[]` define custom character classes. 

### Greedy and Lazy Match

Regex quantifiers are greedy by default. They match as much text as possible. Adding `?` makes them lazy, meaning they only match as much text as necessary.

### Boundaries

Word boundaries `\b` are used to help match whole words with partial matches. They're useful for text analysis.

### Back-references

Back-references, `\1`, `\2`, and so on, are used to refer to previously matched text.

### Look-ahead and Look-behind

Look-ahead (`(?=`) and look-behind (`(?<=`) are used to check if patterns follow other patterns without including them in the match.

## Author

I'm Teylor Smith. New to web development, but excited to keep learning.
Github: https://github.com/teylorsmith34
