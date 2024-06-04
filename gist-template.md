# Regex Baby Steps Tutorial!

Where you wanting to learn a little bit about REGEX or Regular Expression but don't want to overload yourself with to much information at once? Well look no further because today I will show you the very basics of REGEX :D

## Summary

In this short lesson we will cover Anchors, Quantifiers, OR Operators, Character Classes, AND Boundaries! It seems like a lot BUT don't frett I promise its simple once you understand the basics.<br />
"^gr[ae]ys?" and "\bgrays|greys\b" <-- Don't worry I will break these 2 down at the end of the lesson!

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
- [Break-down](#break-down)

## Regex Components

### Anchors
<ins>Anchors</ins> are a meta-character that modify the search location criteria (ctrl+f)! Examples include:<br />
"^" states that it is at the start of a string or line<br />
"$" states that is is at the end of a string or line<br />
"\A" looks at the start of a string or line<br />
"\z" looks at the end of a string or line<br />

### Quantifiers
<ins>Quantifiers</ins> are meta-characters that modify the previous character amounts for seraching. (ctrl+f)!
Basically stating how many meta-characters of a said type to search for...
Examples include:<br />
 "*" looks for 0 or more of said characters<br />
 "+" looks for 1 or more of said characters<br />
 "?" makes it state 0 or 1 (meaning it could or couldnt have it (its a possibility))<br />
 "{Min amount, Max amount}" <-- This looks for an amount IE between 4 and 10 characters<br />
 "{amount}" <-- This looks for a set amount of characters IE 8<br />
 "{amount,}" <-- This looks for a set amount of characters and more IE 5 and up<br />

### OR Operator
<ins>OR Operators</ins> are simple coding! "|" is the "OR" in coding, so stating that you wanna search for the words:<br />
"credit" or "debit"<br />
 instead you would put: <br />
 "credit|debit"<br />

### Character Classes
<ins>Character Classes</ins> can be simple or complex depending on where it will be used, putting ANY meta-character inside a set of brackets - [] will looks for a set character through the "list of character" IE:<br />
"gr[ae]y" looks for the word gr[a]y or gr[e]y<br />
You can also have it look for bigger groupings such as:<br />
"[0-5a-tA-T]" this will look for any number between 1 and 5, then look for lower case letters between a and t, then uppercase letters between A and T 

### Flags
**COMING SOON**
### Grouping and Capturing
**COMING SOON**
### Bracket Expressions
**COMING SOON**
### Greedy and Lazy Match
**COMING SOON**
### Boundaries
<ins>Boundaries</ins> are a meta-character that looks for things within itself for example:<br />
"\b or \B" will look for things that you search within ALL words if the boundaries are set properly<br />
    Setting the boundaries as follows:<br /> 
    "\bword" looks for things like "word" or "passWORD" where "word" is at the end<br />
    "word\b" looks for things like "word" or "WORDscapes" where "word" is at the start<br />
    "\bword\b" looks for things like "afterWORDs" or "sWORDsmanship" where "word" is fully surrounded by other characters but never the word itself or at the start or end of it<br />
    where as "\bword|word\b" does the opposite and looks for things like "WORDlessness" or "broadsWORD" where "word" IS at the start or end but never incased<br />
    ALL BOUNDARIES CAN BE \b or \B ON DEPENDING ON WHAT YOU ARE LOOKING FOR - must remain the same for start and end CANNOT change from \b to \B

### Back-references
**COMING SOON**
### Look-ahead and Look-behind
**COMING SOON**

### Break-down
This section is to break down EACH piece of the "search" critera at top of page:<br />
^gr[ae]ys? :<br />
^ This states that we are looking for anything with "g" in the 1st position<br />
[ae] is looking for an "a" or an "e" in the 3rd position<br />
? is saying that an "s" may or may not be there but look for it anyway<br />
So ALL the combinations of things we are looking for with this set up is - gray, grays, grey, greys<br />
The easier way to understand this is that all written letters or numbers are just that!<br />

\bgrays|greys\b :<br />
This one starts to look for ANYTHING with the "grays" text line at the END of a word OR ANYTHING with the "greys" text line at the START of a word<br />
This one looks straight forward and thats because it is... The OR operator"|" makes it a little easier to read<br />

Always keep in mind there is SO MANY different things to look forward to with REGEX and A LOT more rules, this lesson was the BARE-MINIMUM of what you need to start searching through your DOCS for faster and easier fixes!
## Author
A little bit about me: I worked as a retail cashier for many years and started to get bored with myself so I joined the United States Navy. While in the USN I learned a little coding from my job there and got really interest so when I left I joined a school called Southern Methodist University to learn MORE about web development and game creation.<br />
Here is a link to my GITHUB profile so you can see some of the work I have done over the few months of learning coding! https://github.com/LLCHernandez
