### identifier
Starts with a letter. Proceeding characters are letters, numbers, or a mix of letters and numbers.

### type
Primitive type. Examples: string, integer, boolean, etc.

### function type
A function type. These are: void, boolean, int and string.

### value
Either an identifier (for a variable), or a literal (for example: 1, "Hello Astro").

### location
The location for a file, for example `me.astroknight.MyClass`. Dots represent backslashes.

### condition
A condition, for example `5 < 6`.

### codeblock
A block of code. This block of code can contain any valid code.

<br />

## Declarations
### Class declaration
`class <class identifier> { <codeblock> }` <br />
*Has to contain a Main method.*

### Method/function declaration
`function <function type> <name identifier>(<variables>) { <codeblock> }` <br />
*Creates a function that is callable from any file, as long as it is linked.*

### Variable declaration
`var <type> <name identifier>;` <br />
*Creates an empty variable.* <br />
`var <type> <name identifier> = <value>;` <br />
*Creates a variable containing a value.*

<br />

## Statements
### Comments
`// This is a single line comment.` <br />
*A single line comment that is ignored by the compiler.* <br />
`/* This is a multi line comment. */` <br />
*A multi line comment that is ignored by the compiler.*

### Import statement
`import <location>;` <br />
*Imports a file. This import needs to be stored in a variable later.* <br />
`import <location> as <name identifier>;` <br />
*Imports a file. This import is stored in a variable. `<name identifier>` is the variable name.*

### Print statement
`System.print(<value>);` <br />
*Prints a value. This can be an integer or a string.*

### If, elseif, else statement
`if (<condition>) { <codeblock> }` <br />
*If the condition is true, it will execute the codeblock.* <br />
`if (<condition>) { <codeblock> } else { <codeblock> }` <br />
*If the condition is false, it will execute the codeblock inside the `else` statement.* <br />
`if (<condition>) { <codeblock> } elseif (<condition>) { <codeblock> } else { <codeblock> }` <br />
*If the condition is false, it will check if the condition of the `elseif` statement is true. If it is, it will execute the codeblock inside it. If false, it will execute the `else` statement's codeblock.*