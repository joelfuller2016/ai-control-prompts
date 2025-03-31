# Coding Prompts

These prompts are designed to help you use AI for various coding tasks, from pair programming to code review and refactoring.

### Title: Code Refactoring Assistant
**Tags**: coding, refactoring, code-cleanup, technical-debt  
**Prompt**: "Review the following legacy code and suggest modern refactoring improvements while preserving functionality. Focus on removing code smells, improving readability, and applying best practices for this language. For each suggested change, explain the rationale, the specific pattern or principle being applied, and provide the refactored version:

```
[PASTE CODE HERE]
```

After suggesting individual improvements, provide a complete refactored version of the entire codebase with all improvements applied. Finally, suggest any tests that should be written to verify the refactored code maintains the original functionality."

### Title: Pair Programming Guide
**Tags**: coding, pair-programming, collaboration, code-review  
**Prompt**: "I'd like you to act as my pair programming partner as I work on [PROJECT/FEATURE DESCRIPTION]. We'll follow a collaborative approach where I'll share my code and thought process, and you'll help by:

1. Asking clarifying questions about requirements or edge cases I might be missing
2. Suggesting alternative approaches when you see potential improvements
3. Pointing out potential bugs or edge cases in my implementation
4. Offering code reviews with specific, actionable feedback
5. Helping me debug issues by suggesting targeted troubleshooting steps

Here's what I'm working on currently:
[CURRENT CODE OR PROBLEM DESCRIPTION]

What questions do you have about what I'm trying to accomplish, and what initial thoughts or suggestions can you offer?"

### Title: Algorithm Design and Optimization
**Tags**: coding, algorithms, optimization, problem-solving  
**Prompt**: "I need to design an efficient algorithm for the following problem: [PROBLEM DESCRIPTION]. Please help me by:

1. Breaking down the problem and identifying the key challenges
2. Suggesting multiple possible approaches, from brute force to optimized solutions
3. Analyzing the time and space complexity of each approach
4. Recommending the best approach based on my constraints: [CONSTRAINTS]
5. Providing pseudocode for the recommended solution
6. Identifying potential edge cases and how to handle them

Once we've settled on an approach, help me implement it in [PROGRAMMING LANGUAGE] with clean, well-commented code."

### Title: Code Documentation Generator
**Tags**: coding, documentation, technical-writing, code-quality  
**Prompt**: "I need comprehensive documentation for the following code. Create documentation that includes:

1. A high-level overview of what the code does and its purpose
2. Function-by-function documentation with:
   - Function purpose
   - Parameters and return values (with types)
   - Examples of usage
   - Any side effects or exceptions that might be thrown
3. Key algorithms or workflows explained in plain language
4. Architectural decisions and patterns used
5. Dependencies and their purposes
6. Installation and setup instructions
7. Common usage scenarios with example code

Here's the code to document:

```
[PASTE CODE HERE]
```

Format the documentation in Markdown, organized in a logical structure that would be helpful for both new and experienced developers."
