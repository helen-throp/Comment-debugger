Maybe just try to implement for Python or Java then rescale to other languages?

- Function which detects extension (and thus language) of code file
- Retrieve the character which marks a comment in that language from somewhere
(Or maybe just write separate functions for each language ... but there's a lot of languages)
- Use AI to interpret plaintext of comment
- Link each comment to relevant code [but how do we know what is relevant code?]
(e.g. a comment above a function may refer to whole function
a comment on a line may refer to many lines of code beneath or one)
- Detect whether text of comment actually corresponds to current action of code
- Return discrepancies
- Maybe look into giving option to just sync comments with code?
(Could lead to 'fun' results but AI can be convincing e.g. ChatGPT)