# REGEX TUTORIAL, Match URLs

Regular expressions (regex) are powerful tools for pattern matching and validation. In this tutorial, we will explore how to create a regex pattern to match URLs. Whether you're building a web crawler, validating user input, or need to extract links from text, understanding how to match URLs with regex is a valuable skill. We'll break down each component of the regex pattern, explaining its purpose and how it contributes to the overall URL matching process.

## Summary

The regex pattern we'll create to match URLs is a comprehensive one that covers various URL structures, including HTTP, HTTPS, FTP, and more.

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
We'll use ^ and $ to ensure the URL matches the entire string.

1. Anchors:

        ^ asserts the start of the string.
        $ asserts the end of the string.
        Together, ^ and $ ensure the URL pattern matches the entire string, not just a part of it.


### Quantifiers
We'll use *, +, and {} to match repetitive elements in the URL.

2. Quantifiers:

        * matches zero or more occurrences.
        + matches one or more occurrences.
        {} allows us to specify a precise number of occurrences. For example, {1,3} matches between 1 and 3 times.


### OR Operator
We'll use | to handle multiple URL schemes.

3. OR Operator:

        | allows us to specify alternatives. For example, (http|https) matches either "http" or "https".


### Character Classes
We'll use [...] to match characters for specific parts of the URL.

4. Character Classes:

        [...] defines a character class. For example, [a-zA-Z] matches any single uppercase or lowercase letter.


### Flags
We'll discuss flags like i for case-insensitive matching.

5. Flags:

        Flags like i make the pattern case-insensitive. For instance, /pattern/i would match "Pattern" as well as "pattern".

### Grouping and Capturing
We'll use (...) to group and capture parts of the URL.

6. Grouping and Capturing:

        (...) groups elements together. For example, (www\..+\.com) captures a URL starting with "www" and ending with ".com".


### Bracket Expressions
We'll use [...] for character alternatives.

7. Bracket Expressions:

        [...] defines character alternatives. For example, [0-9] matches any digit from 0 to 9.


### Greedy and Lazy Match
We'll explain the concept of greedy and lazy matching with * and *?.

8. Greedy and Lazy Match:

        * is greedy and matches as much as possible.
        *? is lazy and matches as little as possible.


### Boundaries
We'll use \b to ensure our pattern doesn't match within larger words.

9. Boundaries:

        \b ensures that the pattern matches whole words or URLs without being part of larger words.


### Back-references
We'll demonstrate how to reference captured groups.

10. Back-references:

        \1, \2, etc., refer to captured groups. You can use them for validation or extraction.


### Look-ahead and Look-behind
We'll explore positive and negative lookaheads and lookbehinds to ensure proper URL validation.

11. Look-ahead and Look-behind:

        Positive and negative lookaheads and lookbehinds allow you to specify conditions for matching without including them in the result.


## Author

Daniel is a dynamic and enthusiastic junior software developer who has embarked on an exciting journey in the world of programming. He always had a passion for technology and a desire to create innovative solutions to real-world problems.

[Github Profile JMorante89](https://github.com/JMorante89)

