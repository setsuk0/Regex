# Hex Color Value Regex Tutorial

Welcome to this beginner-friendly tutorial on regular expressions! In this tutorial, we will explore the regular expression used to match hex color values commonly used in web development. Let's dive in!

## Overview

The regular expression we will be discussing is: `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`. This regex allows us to validate and match hex color values, supporting both the 3-digit and 6-digit formats and allowing for an optional leading '#' symbol.

## Table of Contents

- [Anchors (^ and $)](#anchors)
- [Quantifiers ({})](#quantifiers)
- [OR Operator (|)](#or-operator)
- [Character Classes ([a-f0-9])](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing ( )](#grouping-and-capturing)
- [Bracket Expressions ([ ])](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Understanding the Regex Components

### Anchors (^ and $)

The caret `^` and dollar sign `$` are anchors used in the regex. They ensure that the matching should start from the beginning of the string and end at its last character, respectively.

### Quantifiers ({})

The curly braces `{}` are used as quantifiers in the regex. `{6}` specifies that the preceding character set `[a-f0-9]` should occur exactly 6 times, matching the 6-digit hex color format. Similarly, `{3}` specifies 3 occurrences, matching the 3-digit format.

### OR Operator (|)

The pipe symbol `|` acts as the OR operator in the regex. It provides two alternatives for matching hex color values: either a 6-digit format or a 3-digit format.

### Character Classes ([a-f0-9])

The character class `[a-f0-9]` matches any lowercase letter from 'a' to 'f' or any digit from 0 to 9. This ensures we only match valid hexadecimal characters in the color value.

### Flags

In this regex, no flags are used. Flags are optional modifiers that can change the regex behavior, such as case insensitivity or global matching.

### Grouping and Capturing ( )

The parentheses `()` are used for grouping and capturing in the regex. They group together the character set and the OR operator. This allows us to capture the matched color value for further processing, if needed.

### Bracket Expressions ([ ])

There are no bracket expressions used in this regex. Bracket expressions are used to define sets of characters, but they are not required here.

### Greedy and Lazy Match

There are no specific quantifiers that exhibit greedy or lazy behavior in this regex. The quantifiers used are by default greedy.

### Boundaries

The regex does not include specific boundary indicators. It is designed to match the entire string from start to end.

### Back-references

Back-references are not used in this regex. They allow referring back to captured groups within the pattern itself.

### Look-ahead and Look-behind

Look-ahead and look-behind assertions are not used in this regex. They define conditions ahead or behind the current position for a match to occur.

## About the Author

This tutorial was written by Jen. You can find more coding examples on (https://github.com/setsuk0).
