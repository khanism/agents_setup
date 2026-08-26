# Don't excessively comment code
- Assume an expert is reading the code, meaning don't make comments where the code's intent is obvious.
- Don't create bulky comments, be expressive and never use more than one line for a comment, summarizing in 50 letters maximum.

# Keep the code efficient in the lines of code count
- Always prefer the most minimum code that does the job, even if it means some error handling is missing.
- Prefer simple code over more complex abstractions.
- Avoid changes that are only white spaces or line breaks, if they don't contribute to the program compiling or running correctly

# Keep token usage as efficient as possible
- Wherever possible safe on token usage as much as possible.
- Don't update test files everytime we change something in the code base, event if that means the tests break, unless I explicitely want the unit tests to be updated.

# Prefer standard library dependencies over third party dependencies
- Try to avoid using third-party libraries and prefer the language's standard libraries.
- Should you intend to add a third-party dependency, always explicitly mention that and always ask for permission, even if you were granted permission to execute tasks autonomously.
