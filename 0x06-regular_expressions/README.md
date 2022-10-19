#		REGULAR EXPRESSIONS
This is a set of characters that define a search pattern, used with string matching.
"Regex flavours" is wheb two or more applications use different implementation of regular expressions.
##	Writting regular Expressions.
__OPTIONAL ITEMS__
1.	Question Mark:
Its called a quantifier. A regex followed by question mark matches zero or one occurences of reqular expression
```
	colou?r
```
The above code matches both `color` and `colour. It tells the computer it might or might not be present.
2.	Parenteses():
This is a grouping character which combines different symbols of regular expression to act as a single unit and behave as block 
```
	Feb(ruary)?29(th)
```
This matches `Feb 29th`, `February 29th`, `Feb 29`, `February 29`. Items inside parentheses are optional.
