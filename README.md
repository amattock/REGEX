# REGEX
 
This Regex tutorial has been created to provide the reader with a better understanding of what a regex is, how it works, and how it can be used to validate user input.

## Summary

A regex (short for regular expression), is a sequence of characters that outlines a specific search pattern or criteria. When a regex is included in code or search algorithms, it can be used to find certain patterns of characters contained within a string, find and replace a character or sequence of characters within a string, or, validate an input.

The example below demonstrates how a regular expression can be used to verify that user input is a valid email address:

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

As you can see, the regex above is a sequence of characters that outlines a specific search pattern. In this case, the pattern is a valid email address. The regex is used to validate user input by comparing the input to the pattern. If the input matches the pattern, the input is considered valid.

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

Anchors are used to match a position within a string. The two most commonly used anchors are the circumflex or caret (^) and the dollar sign ($). The caret is used to match the beginning of a string, while the dollar sign is used to match the end of a string.

### Quantifiers

Quantifiers specify the number of times a character or group of characters are allowed to be repeated. Commonly used quantifiers include the asterisk (*), the plus sign (+), and the question mark (?). Asterisk's are used to match zero or more occurrences of the preceding character or group of characters.

### Grouping Constructs

Grouping constructs group characters together. Grouping constructs are created using parentheses. Grouping constructs are used to apply quantifiers to multiple characters or groups of characters.

### Bracket Expressions

Bracket expressions are used to match a single character from a group of characters. Bracket expressions are created using square brackets([]). Bracket expressions can be used to match a single character from a group of characters, or, a range of characters.

### Character Classes

A character class serves to specify a group of characters permitted in input strings to facilitate a successful match. The previously discussed bracket expressions are illustrations of this concept. Two additional instances can be found in our email example. The period (.) matches any character except for the newline character (\n). 

### The OR Operator

In the realm of Regex, the vertical bar character '|' serves as the 'OR' operator. It enables you to define choices within a regex pattern. When you use the '|' symbol, it functions as a separator between distinct patterns or character sequences, signifying that a match can be identified if any of the provided alternatives are present."

### Flags

Regex flags serve to adjust how a regular expression behaves. These flags are added at the end of a regex pattern, typically following a forward slash (/). In this discussion, we'll delve into two specific flags: the global (g) and case-insensitive (i) flags. The global flag, denoted by 'g,' is employed to locate all occurrences of a pattern within a string, rather than halting after the first match. The case-insensitive flag, indicated by 'i,' is used to disregard letter case distinctions when searching for a pattern within a string

### Character Escapes

The final aspect we'll explore pertains to character escapes. A character escape involves the use of a backslash to instruct a regex to examine the character immediately following the backslash, rather than treating it as a literal character. In the example mentioned earlier, you can find an instance, (.), which indicates our intention for the expression to specifically search for a period (.) rather than interpreting it as a part of the character class that shares the same symbol.

## Author

Currently work in Agriculture predominantly in the research operations space, currently embarking on learning a new skillset in the area of web development.  

## Sources 

Regex tutorial -https://www3.ntu.edu.sg/home/ehchua/programming/howto/Regexe.html#:~:text=Regex%20recognizes%20common%20escape%20sequences,for%20a%208%2Ddigit%20Unicode.
