# Regex Gist

As a web developer, you can use regex to find and replace text in your code. This gist is an example of how you can use regex to find and replace text in your code.

## Summary

A Regex or Regular Expression is a sequence of characters that forms a search pattern. When you type a search pattern into a text editor, it's called a regex.

Here we will look at HTML tags and their attributes.

Example: /^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/

Below we will explore the different components of this regex.

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

#### ^ - Matches the beginning of a string
#### $ - Matches the end of a string

#### \b\B - Matches the beginning or end of a string

### Quantifiers

#### * - 0 or more times
#### + - 1 or more times
#### ? - 0 or 1 times
#### a{5}a{2,} - 5 a's and 2 or more a's
#### a{2,5} - 2 to 5 a's
#### {3,5} - 3 to 5 times
#### a+?a{2,}? - 2 or more a's
#### ab|cd - Either match ab or cd

### Grouping Constructs

#### () - Grouping
#### | - OR
#### (?=...) - Positive lookahead
#### (?!...) - Negative lookahead
#### (?<=...) - Positive lookbehind
#### (?<!...) - Negative lookbehind
#### (ABC) - Capturing groups tokens together and returns them as an array
#### \1 - is a reference to the first capturing group
#### (?:...) - Non-capturing groups
#### (?<name>...) - Named capturing groups

### Bracket Expressions

#### [...] - Character class
#### [^...] - Negated character class
#### [a-z] - Character class
#### [^a-z] - Negated character class
#### [ABC] - Character class
#### [^ABC] - Negated character class
#### [\s\S] - Any character 


### Character Classes

#### \w - Word character
#### \W - Non-word character
#### \d - Digit
#### \D - Non-digit
#### \s - Whitespace
#### \S - Non-whitespace
#### \p - Unicode property
#### \P - Non-Unicode property
#### \b - Word boundary
#### \B - Non-word boundary
#### . - Any character

### The OR Operator

#### | - OR operator matches either of the two patterns

### Flags

#### i - Case-insensitive (ignores case)
#### m - Multiline (finds newline characters)
#### s - Singleline (finds newline characters)
#### x - Extended (allows comments)
#### u - Unicode (finds unicode characters)
#### g - Global (finds all matches)
#### y - Verbose (finds newline characters)

### Character Escapes

#### \n - Newline character
#### \t - Tab character
#### \r - Carriage return character
#### \f - Form feed character
#### \b - Backspace character
#### \a - Bell character
#### \v - Vertical tab character

## Author
### Nicholas Eggleston 
A student through edX Bootcamp @ Michigan State University

Please contact me on 
[GitHub Profile](https://github.com/nickegg11)
### Gist Link
[Gist](https://gist.github.com/nickegg11/97b21a7b0938fc423208e82ce8082fe8)