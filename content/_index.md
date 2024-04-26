---
title: "UCSC"
date: 2019-11-19T17:21:20+01:00
page: true
---

# CSE 130 QUIZ PREP - WEEK 3

<!-- A hugo shortcode for writing quizzes with a markdown-like syntax: https://github.com/bonartm/hugo-quiz. -->

<!-- **Try out the live code editor: https://bonartm.github.io/quizdown-live-editor/** -->


{{< quizdown >}}

# Which of the following correctly describes the behavior of local static variables within a function?

- [ ] The variable is initialized on each call to the function.
- [x] The variable retains its value between function calls.
- [ ] The variable is accessible from other functions within the same file.
- [ ] The variable is stored on the heap.

# How does the C runtime environment typically initialize global variables that are not explicitly initialized by the programmer?

- [ ] It initializes them to one.
- [ ] It leaves them uninitialized.
- [x] It initializes them to zero.
- [ ] It generates a compile-time error.

# What happens to the value of a local variable in C if it is not explicitly initialized?

- [ ] It is initialized to zero by the compiler.
- [x] It holds a garbage value, depending on what previously occupied its memory location.
- [ ] It is automatically set to null.
- [ ] It triggers a compiler error.

# In the context of C programming, what is the effect of declaring a variable as 'static' inside a function?

- [ ] The variable's value is reset every time the function is invoked.
- [x] The variable behaves like a global variable, but with function scope.
- [ ] The variable is shared among all functions in the program.
- [ ] The variable can be accessed from outside the file.

# What is the typical initial value assigned to static variables in C when they are not explicitly initialized?

- [ ] Null
- [x] Zero
- [ ] One
- [ ] Undefined

# What characteristic does a local static variable share with a global variable?

- [ ] It is initialized every time the function is called.
- [x] It retains its value between function calls.
- [ ] It is accessible across different files.
- [ ] It does not retain its value between function calls.

# In C programming, how are global variables initialized if no initial value is provided?

- [ ] They start with the last stored value in memory.
- [x] They are initialized to zero.
- [ ] They are set to NULL.
- [ ] They remain uninitialized.

# What default behavior affects local variables in C when they are not explicitly initialized?

- [ ] They are automatically initialized to zero.
- [ ] They default to NULL.
- [x] They contain garbage values based on memory content.
- [ ] They cause an immediate runtime error.

# Which statement best describes the scope and storage of static variables within a function in C?

- [ ] They have global scope and global storage.
- [ ] They have local scope and are stored like local variables.
- [x] They have local scope and global storage.
- [ ] They have global scope but are only accessible within the function.

# What is the initialization behavior of static local variables in C programming when not explicitly initialized?

- [ ] They are set to NULL.
- [ ] They are left uninitialized.
- [x] They are initialized to zero.
- [ ] They start with a random memory value.

# Which function in regex.h is used to compile a regular expression into an intermediate form?

- [ ] regexec()
- [x] regcomp()
- [ ] regfree()
- [ ] regerror()

# What does regexec() primarily accomplish in the context of regular expressions?

- [ ] It frees allocated memory associated with regular expressions.
- [x] It processes a string against a compiled regular expression.
- [ ] It compiles the regular expression into a usable format.
- [ ] It checks for errors in the regular expression syntax.

# What is the purpose of using parentheses in a regular expression?

- [ ] To specify optional patterns
- [x] To group parts of the pattern and capture the group for further processing
- [ ] To indicate repetition of the preceding character
- [ ] To escape special characters

# In the context of regex.h, what is the significance of using flags like REG_EXTENDED?

- [ ] To allow for basic POSIX regular expressions
- [x] To enable extended functionality in POSIX regular expressions
- [ ] To compile the regular expression without any errors
- [ ] To interpret newline characters as whitespace

# What does the regcomp() function do when provided with a regular expression?

- [ ] It matches a regular expression against a given text.
- [ ] It interprets and executes a regular expression.
- [x] It compiles a regular expression into a format that can be used by other regex functions.
- [ ] It generates a regular expression based on user input.

# Which function is called to free memory associated with a regular expression compiled by regcomp()?

- [x] regfree()
- [ ] regexec()
- [ ] regerror()
- [ ] regend()

# What is the main advantage of separating the compilation and execution stages in regular expression processing?

- [ ] Increases memory usage efficiency.
- [ ] Allows for more complex regular expressions.
- [x] Enhances performance by not recompiling regular expressions.
- [ ] Simplifies the debugging of regular expressions.

# How are substrings matched within a regular expression using parentheses?

- [ ] Substrings are ignored unless specified by special flags.
- [x] Substrings can be captured for use in later processing.
- [ ] Substrings are automatically replaced in the source string.
- [ ] Substrings modify the behavior of regex meta-characters.

# What function is used to compile a regular expression in the context of the lecture discussion?

- [ ] RegNew
- [x] RegCompile
- [ ] RegExec
- [ ] RegTest

# Which of the following return values from RegExec indicates a successful match?

- [ ] 1
- [x] 0
- [ ] -1
- [ ] None of the above

# What does the RMEO pointer represent in the regular expression functions discussed?

- [ ] The start of the match
- [ ] The end of the match
- [x] The character after the end of the match
- [ ] The length of the match

# What should be used to handle a match that includes zero or more occurrences of any character except a newline?

- [ ] DotStar
- [ ] DotPlus
- [x] DotStar with RegNewLine flag
- [ ] None of the above

# What problem arises if RegExec matches an empty string in a loop without proper conditions to exit?

- [ ] It terminates the program
- [x] It leads to an infinite loop
- [ ] It skips the match
- [ ] It causes a syntax error

# What should be adjusted if a regular expression’s RMSO gives a value of -1?

- [ ] The entire regular expression
- [ ] The matching string
- [x] The loop's exit condition
- [ ] The starting offset

# In a matching operation, what does a non-zero return value from RegExec indicate?

- [ ] A successful match
- [x] A failure to match
- [ ] A syntax error in the regular expression
- [ ] None of the above

# What is a likely consequence of using .* with the RegNewLine field in a regular expression?

- [ ] Matches only the first occurrence
- [ ] Skips newline characters in matches
- [x] Can cause an infinite loop if matching against an empty string
- [ ] Matches multiline strings without issues

# Which parameter of RegExec would you adjust to start the next match immediately after the end of the previous match?

- [ ] RMSO
- [ ] RMEO
- [x] The string pointer s
- [ ] The pattern buffer

# What could be the effect of not managing the pointer to the string being searched when using RegExec in a loop?

- [x] The pointer remains constant, causing repetitive searches in the same location.
- [ ] The pointer automatically resets to the beginning of the string.
- [ ] The search skips forward unpredictably.
- [ ] The pointer moves to the end of the string, terminating the search early.

# Which function might be called when there is a need to parse a regular expression into a usable data structure?

- [ ] RegNew
- [x] RegCompile
- [ ] RegExec
- [ ] RegTest

# What is indicated by a starting offset (RMSO) of minus one in the results of a regular expression match attempt?

- [ ] A successful match
- [ ] An error in the regular expression syntax
- [x] No match was found
- [ ] The match was found at the beginning of the string

# In a programming context discussed, what does setting the RegNewLine flag affect in a regular expression operation?

- [ ] It allows the regular expression to match new lines within the string.
- [x] It prevents the regular expression from matching across multiple lines.
- [ ] It causes the regular expression to ignore whitespace.
- [ ] It increases the efficiency of matching operations.

# What could be the result of improperly managing a loop when RegExec always returns a match for an empty string due to the use of .* with RegNewLine?

- [ ] Execution exits the loop immediately.
- [x] An infinite loop is created.
- [ ] The matching operation skips to the end of the string.
- [ ] The loop processes each character individually.

# When a local variable is declared within a function without an initializer, what value does it contain?

- [ ] Zero
- [x] Random memory content
- [ ] NULL
- [ ] It is automatically initialized by the compiler

# What does the static keyword imply for a variable declared inside a function regarding its storage duration?

- [ ] Its duration is limited to the function call.
- [x] Its value persists for the duration of the program execution.
- [ ] It is stored on the heap.
- [ ] It is shared among all instances of the function.

# How are uninitialized global variables treated differently from uninitialized local variables in C?

- [x] Global variables are initialized to zero, while local variables contain garbage values.
- [ ] Both are initialized to zero.
- [ ] Both contain garbage values.
- [ ] Global variables contain garbage values, while local variables are initialized to zero.

# What is the default behavior of a static local variable regarding initialization if not explicitly initialized?

- [x] It is initialized to zero.
- [ ] It contains a random value.
- [ ] It remains NULL until assigned.
- [ ] It is initialized to one.

# In C programming, which of the following best describes the scope of a static variable declared within a function?

- [ ] Global scope and local storage
- [x] Local scope and global storage
- [ ] Local scope and local storage
- [ ] Global scope and global storage

# What is the purpose of the regexec() function in the regular expression library?

- [x] To search a text for a pattern defined by a compiled regular expression.
- [ ] To compile a regular expression into a searchable pattern.
- [ ] To free the memory allocated to a compiled regular expression.
- [ ] To report errors encountered during the compilation or execution of a regular expression.

# In the context of regular expressions, what does the REG_EXTENDED flag enable?

- [x] It allows the use of extended regular expression syntax for more complex patterns.
- [ ] It provides compatibility with older regular expression engines.
- [ ] It limits the regular expression to basic POSIX functionality.
- [ ] It ensures thread safety during regex operations.

# When using regcomp() and regexec(), what does compiling the regular expression into an intermediate form before execution achieve?

- [ ] Reduces the number of supported regex features to enhance security.
- [x] Allows the expression to be used multiple times without recompilation, enhancing performance.
- [ ] Automatically handles memory management for regular expression objects.
- [ ] Simplifies the API for new developers by abstracting complexity.

# How does the use of parentheses affect the parsing of groups in a regular expression?

- [ ] Parentheses are used to specify which parts of the pattern are optional.
- [x] They capture substrings of the matched string, which can be accessed after execution.
- [ ] Parentheses alter the priority of the regex operators within.
- [ ] They serve as escape characters for special regex symbols.

# What would be the effect of a regular expression compiled with an error in its syntax when used in RegExec?

- [ ] The program prints the match regardless of errors.
- [ ] The function returns zero, indicating a successful match.
- [x] The compilation fails, and the program may exit.
- [ ] The regular expression matches the entire string by default.

# Which parameter in the RegExec function is used to iterate over multiple matches in a given string?

- [ ] The pattern buffer
- [ ] The match array
- [x] The string pointer
- [ ] The flags parameter

# What must be modified to prevent an infinite loop when matching an empty string using .* in a loop?

- [ ] Increase the string pointer by one after each iteration.
- [x] Modify the regular expression to match one or more characters.
- [ ] Check for a non-zero return value before continuing the loop.
- [ ] Reset the regular expression after each match.

# In a loop where RegExec is used to find matches, what does setting the RMEO to point to the character after the end of a match facilitate?

- [x] It helps in adjusting the string pointer to bypass the matched text.
- [ ] It indicates the start of the next possible match.
- [ ] It prevents the regular expression from matching the same text repeatedly.
- [ ] It resets the regular expression to its initial state.

# Considering the use of RegExec in a programming example, what would be a crucial condition to include to ensure the loop exits after failing to find a match?

- [ ] Check if the starting offset is zero.
- [x] Break the loop if RegExec returns non-zero.
- [ ] Repeat the match until the string ends.
- [ ] Reset the regular expression before each iteration.

<!-- ---
primary_color: steelblue
---

# The sound of dog

---
shuffle_answers: false
---

What do dogs sound like?

> ![](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2d/Dog_-_%E0%B4%A8%E0%B4%BE%E0%B4%AF-6.JPG/150px-Dog_-_%E0%B4%A8%E0%B4%BE%E0%B4%AF-6.JPG)

```python
class Dog(Animal):
    def __init__(self, name):
        self.name = name
```

- [ ] yes
- [ ] no
- [ ] `self.sound = "meow"`
- [x] wuff

# Put the [days](https://en.wikipedia.org/wiki/Day) in order!

> Monday is the *first* day of the week.

1. Monday
2. Tuesday
3. Wednesday
4. Friday
5. Saturday  


# Optional Math formula rendering

$$
x = \frac{2+2}{\sqrt{a^2+b^2}}
$$


- [ ] yes
- [ ] no -->

{{< /quizdown >}}
