# linux-shell-scripting-comments
This project demonstrate effective commenting practices in shell scripting. Comments enhances script readability, maintainability and collaboration.

## Comments
Comments are lines in code that are ignored by the interpreter. Comments helps to document the purpose and logic of your code, making it easier for others (and yourself) to follow and understand the script's functionality.

### Single line comment
A single line comment in Bash starts with the '#' symbol. Anything following the symbol on the same line is treated as a comment and is not executed.

```bash
# This is a single line comment in Bash
echo "Hello, welcome to shell scripting, now you are learning to comment on your code."
```

### Multiple Single line comments
To write more than one line of comments, multiple single-line comments can be used.

```bash
# This is one line of comment
# This is another line of comment to demonstrate multiple single line comments
echo "Here is the actual code that will be executed"
```

![Single and Multi-line Comments](scripting-comments.png)

### Best Commenting practices
1. Clarity: Write clear and concise comments that explain the 'why' behind the code, not just the "what".
2. Maintainability: Keep comments updated as you modify the code to remain relevant and useful.
3. Usefulness: Comment on complex or non-obvious parts of the script to provide insights into your thought process and decision-making.
4. Avoid overcommenting: Don't comment on every line of code especially if the code is self explanatory.

### Conclusion
Effective commenting is a critical practice in shell scripting that significantly improves code quality. By following best practices —such as writing clear, concise, and relevant comments while avoiding redundancy, developers can create scripts that are easier to understand, maintain, and share. Adopting these habits fosters better collaboration and ensures that scripts remain accessible and useful over time, benefiting both the original author and future contributors.