# Clean Code
## Why
Dirty shit will be re-written.
Messes will compound to slow you down.
## What
Performant does not "tempt" messy code. People make bad code worse
Done one thing well
UNIX Philosophy: Make it work, Make it right, Make it fast
Boy Scout Principle: leave the campground cleaner than you found it
## How
### Names
Use intention revealing names
Not just simplistic but also explicit
Avoid disinformation. Avoid names which vary in small differences
Meaningful distinctions between variables. Avoid noise words
Use pronounceable names
Avoid mental mapping
Class nmes and objects should have noun/noun phrases
Methods should be verb/verb phrases
* **accessors** prefix with **get**
* **mutators** prefixed with **set**
* **predicates** prefixed with **is**
One word per concept
Avoid overloaded constructors
Dont pun
Use CS where necessary
Add meaningful contexts

### Functions
Keep your functions small
One/two levels of indentation at most. Any more means the function is not doing just one thing.
One level of abstraction per function
Avoid switch statements. Don't completely avoid. Can keep in lower level functions.
#### Arguments
* Zero: ideal
* One: better
* Two: ok
* Three: avoid where possible
Don't use flag arguments. Flags says the function is not doing one thing.

Functions should either do something or ask something
Prefer exceptions to returning error codes
Don't repeat yourself. Though not all duplication is bad.
Don't create overly complex abstractions

### Comments
Comments do not make up for bad code
Explain yourself in code, not in comments
#### Good comments
Explanation of intent
Clarification. Translate the meaning of something that might be confusing. Clarify the message is something that cannot be changed.
TODO comments
Warning of consequences
Amplification. Situation where code looks trivial but does something important
#### Bad comment

### Code formatting
detail should increase as we go downward
source file name should be concise
line breaks into separate concepts
concepts clearly related shoul be close

you shouldnt have to scroll horizontally

# Zen of Python
viewable by entering `import this` in a python shell

	Beautiful is better than ugly.
	Explicit is better than implicit.
	Simple is better than complex.
	Complex is better than complicated.
	Flat is better than nested.
	Sparse is better than dense.
	Readability counts.
	Special cases aren't special enough to break the rules.
	Although practicality beats purity.
	Errors should never pass silently.
	Unless explicitly silenced.
	In the face of ambiguity, refuse the temptation to guess.
	There should be one-- and preferably only one --obvious way to do it.
	Although that way may not be obvious at first unless you're Dutch.
	Now is better than never.
	Although never is often better than *right* now.
	If the implementation is hard to explain, it's a bad idea.
	If the implementation is easy to explain, it may be a good idea.
	Namespaces are one honking great idea -- let's do more of those!

# PEP8
Styleguide for python
## Naming
Function, variable: lowercase, snake_case
Class: PascalCase
Constant: ALLCAPS
Package: lowercase words or words without underscores
## Code layout
top-level functions and classes should be separated by 2 blank lines
methods in a class should have one line between them
Line length 79 chars, but could be extended to 120
Hanging indents