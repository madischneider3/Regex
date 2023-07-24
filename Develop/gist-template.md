# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

The regex I will be describing is a simple one, one that matches a date in the year, month, day format. Here is a snippet of that code:

const dateRegex = /^\d{4}-(0[1-9]|1[0-2])-(0[1-9]|[1-2][0-9]|3[0-1])$/;

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

Regex's are a somewhat language of their own, utilizing characters/patterns to locate, validate, replace, and split strings in a body of code/text.

### Anchors

Anchors are the expressions way of asserting something about the string and its matching process. Here are the anchors in our expression

### Quantifiers

Quantifiers can be classified as greedy(longest match), docile(returns back characters when needed), lazy(shortest match) and finally helpful(expands match when needed). Here are the quantifiers in our expression:

### OR Operator

You can use the OR operator to match charcters/expressions to the right or left of the operator within the regex itself.

### Character Classes

Classes sepeperate the types of charcters within the expression, think letters, digits etc. Some regex environments allow you to do operations within the character classes. You can subtract by matching charcters to one class and not another, you can intersect charcters from one class and another, and union charcacters that belong to multiple classes. 

### Flags

A flag is an optional parameter to add to the expression that modifies the way it searhces. In JavaScript a common example of this is the i flag ignores casing while searching. 

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
