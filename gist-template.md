# RegexTut

Regex: regular expressions are patterns used to search through a string of text, it can check if a string contains a certain letter or phrase. It can also be used for matching, and manipulating strings of text based on a specific pattern. Regex patterns can be used for other tasks such as validation, text extraction, and data transformation. Regular expressions differ based on the programming language.

## Summary

<img width="652" alt="regex" src="https://github.com/KimTurboutique/RegexTut/assets/127644189/95204e17-7d3f-4d22-9330-76856479e5ea">

In this simple regex in Javascript '/' indicates the start of a regular expression, the character set '[ esm ]' was then used to match any character in the set an "e", "s" and a "m" the '\w' matches and word character and the + quantifier matched 1 or more of the proceding tokens. The '/' represents the end of the regular expression and beginning of the expression flags 'g' for the global matching, 'i' for case-insensitive and 'm' for the multiline matching flag. This regex was used to search for characters e,s and m in the string of text which resulted in 11 matches, see below:

<img width="676" alt="regexfull" src="https://github.com/KimTurboutique/RegexTut/assets/127644189/4e3d7470-e3b3-4889-826f-7a0795c00809">


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

The different types of regex components are based on their purpose and the kind of matches/searches they are designed to perform.

### Anchors

Anchors define the positions in the text. For example '^' matches the start of a line or string.

### Quantifiers

These specify how many times a character or group should occur. For example in my regex above I used the '+' quantifier which matches one or more occurences.

### Grouping Constructs

Grouping constructs- group expressions together and captures matched text for later use by using parentheses for example '(abc)'.

### Bracket Expressions

Allows you to define a set of characters that should match a single character at a specific position in the text using square brackets '[. . .]'. They are crucial components of regex also known as character classes, in the example above I used this to match simple characters [ esm] it matched 'e','s', or 'm' in my test paragraph.

### Character Classes

Are the same as bracket expressions. There are different explanations: 1. Simple Character Classes, 2. Negated Character Classes, 3. Combining Character Classes, 4. Escaping Within Character Classes, 5. Special Characters Within Character Classes, etc. They provide you with versatile ways to define sets of characters.

### The OR Operator

The OR operator uses the pipe symbol '|' it allows you to specify between two patterns for example used in my test paragraph below we could specify between two words 'for|my' the pattern would match either "for" or "my" in the text.

<img width="705" alt="OR operator" src="https://github.com/KimTurboutique/RegexTut/assets/127644189/08bc8f44-48a6-465a-b491-41910c3044d1">


### Flags

Flags are modifiers that you can apply to change the way the pattern is matched they control the aspects of matching above I used the global flag 'g' which matches all occurences in the test pargraph not just the first one, secondly I used the case-insensitive flag 'i' which causes the pattern to match regardless of the letter case for example in the first line the word "my" was matched as well as in the second line the word "My" at the beginning was matched as well. I also used the multiline flag to match the start and end of each line. Flags are specific to the programming language; in Javascript they are added to the end of the regex literal.

<img width="711" alt="flags" src="https://github.com/KimTurboutique/RegexTut/assets/127644189/c581b305-c5b4-417d-89cd-5142e5f7c0eb">


### Character Escapes

These are used to match specific characters in a more readable way. In my test I used the '\w' word character which matches any word character including letters, digits, underscores.

## Author

This tutorial was curated by Kimberly R. a committed Full Stack Web Development student that is also a full time parent and business owner who has dedicated time and research to get a better understanding of regular expressions and used that knowledge to put this tutorial together in hopes it will help a fellow web development student like herself understand regex.

* [Author's Github](https://github.com/KimTurboutique)
