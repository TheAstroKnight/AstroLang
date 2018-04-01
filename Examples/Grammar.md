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
`class <class identifier> { <codeblock> }`
*Has to contain a Main method.*

### Method/function declaration
`function <function type> <name identifier>(<variables>) { <codeblock> }`
*Creates a function that is callable from any file, as long as it is linked.*

### Variable declaration
`var <type> <name identifier>;`
*Creates an empty variable.*
`var <type> <name identifier> = <value>;`
*Creates a variable containing a value.*

<br />

## Statements
### Import statement
`import <location>;`
*Imports a file. This import needs to be stored in a variable later.*
`import <location> as <name identifier>;`
*Imports a file. This import is stored in a variable. `<name identifier>` is the variable name.*

### Print statement
`System.print(<value>);`
*Prints a value. This can be an integer or a string.*

### If, elseif, else statement
`if (<condition>) { <codeblock> }`
*If the condition is true, it will execute the codeblock.*
`if (<condition>) { <codeblock> } else { <codeblock> }`
*If the condition is false, it will execute the codeblock inside the `else` statement.*
`if (<condition>) { <codeblock> } elseif (<condition>) { <codeblock> } else { <codeblock> }`
*If the condition is false, it will check if the condition of the `elseif` statement is true. If it is, it will execute the codeblock inside it. If false, it will execute the `else` statement's codeblock.*