#RegExp Object
A regular expression is an object that desrcibes a pattern of characters.
Regular expressions are used to perform pattern matching and "search-and-replace" functions by text.

#Syntax

                    /pattern/modifiers;
                    
#Example

                     var patt = /w3schools/i;
                     
      Example Explained:
      - /w3c schools/i is a regular expression
      - w3schools is a pattern (to be used in a search)
      - i is a modifier (modifies the search to be case-insensitive)
      
#Modifiers
Modifiers are used to perform case-insensitive and global searches:

- i Perform case-insensitive matching
- g Perform a global-match (find all matches rather than stopping at the first match)
- m Perform multiline matches

#Brackets
Brackets are used to find a range of characters:

- [abc] Find any character between the brackets
- [^abc] Find any character not between the brackets
- [0-9] Find any digit between the brackets
- (x|y) Find any of the alternatives specified

#Metacharacters
Metacharacters are characters with a special meanings:

- . Find a single character, except newline or line character
- \w Find a word character
- \W Find a non-word character
- \d Find a digit
- \D Find anon-digit character
- \s Find a whitespace character
- \S Find a non-whitespace character
- \b Find a match at the beginning/end of the word.
- \B Find a match not at the beginning/end of a word
- \0 Find a null character
- \n find  newline character
- \f form feed character
- \r carriage return character
- \t Find a tab character
- \v Find a vertical tab character
- \xxx Find the character specified by the octal number xxx
- \xdd Find the character specified by a hexidecimal number
- \uxxx Find the unicde character specified by a hexidecimal character xxxx

#Quantifiers
- n+ Matches any string that contains at least one n
- n* Matches any string that contains zero or more occurrences of n
- n? Matches any string that contains zero or one occurrences again

      
                     
