# Regex Tutorial

Welcome to the Regex Tutorial! This tutorial aims to provide a comprehensive guide to regular expressions.

## Summary

In this tutorial, we will explore the fundamentals of regular expressions and their usage in pattern matching. We'll cover various components of regex syntax and provide examples to illustrate their functionality.

```regex
^\d{3}-\d{2}-\d{4}$

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
Anchors are used to specify positions in the input string where matches must occur. Examples of anchors include ^ for the start of a line and $ for the end of a line.

### Quantifiers
Quantifiers specify how many instances of the preceding element should be matched. Examples of quantifiers include * for zero or more, + for one or more, and ? for zero or one.

### Grouping Constructs
Grouping constructs allow you to group multiple tokens together as a single unit. This is useful for applying quantifiers or alternation to multiple characters.

### Bracket Expressions
Bracket expressions, also known as character classes, allow you to match any one of a set of characters. For example, [aeiou] matches any vowel.

### Character Classes
Character classes provide a way to match any character from a specified set. For example, \d matches any digit character.

### The OR Operator
The OR operator, represented by |, allows you to specify alternatives in a regex pattern. For example, cat|dog matches either "cat" or "dog".

### Flags
Flags modify the behavior of the regex engine. Common flags include i for case-insensitive matching and g for global matching.

### Character Escapes
Character escapes allow you to match special characters literally instead of interpreting them as part of the regex syntax. For example, \. matches a literal period character.

## Author
This tutorial was written by Alexis Watson. You can find more of my work on my GitHub profile, https://github.com/awatson622.
