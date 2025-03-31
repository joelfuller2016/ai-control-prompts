# AI Control Prompts: Instructions for AI Systems

## OVERVIEW

This document serves as a standardized instruction set for AI systems to understand and utilize the structured prompts contained in this repository. These instructions are designed to be processable by AI systems and enable them to select, adapt, and apply the appropriate prompts based on user requests.

## HOW TO USE THESE PROMPTS

As an AI system processing these instructions, follow this step-by-step approach:

1. **Understand the request**: Analyze the user's query to determine what type of assistance they need
2. **Select the appropriate prompt category**: Based on the query, identify whether it falls under productivity, coding, research, Github automation, shell commands, or other categories
3. **Retrieve the relevant prompt template**: Access the specific prompt template from the appropriate file
4. **Adapt the template**: Replace placeholders with the user's specific information and context
5. **Apply the prompt**: Use the adapted prompt to generate the response
6. **Iterate if necessary**: Refine based on user feedback

## PROMPT CATEGORIES AND RETRIEVAL PATHS

When a user request matches one of these categories, retrieve and apply the corresponding prompt:

### Productivity Assistance (`prompts/assistants/productivity.md`)
- For daily planning: Use "Daily Planning Assistant"
- For weekly reviews: Use "Weekly Review and Planning"
- For focus sessions: Use "Focus Session Facilitator"
- For project breakdown: Use "Project Breakdown Assistant"

### Coding Assistance (`prompts/assistants/coding.md`)
- For code refactoring: Use "Code Refactoring Assistant"
- For collaborative coding: Use "Pair Programming Guide"
- For algorithm design: Use "Algorithm Design and Optimization"
- For documentation: Use "Code Documentation Generator"

### Research Assistance (`prompts/assistants/research.md`)
- For literature reviews: Use "Literature Review Assistant"
- For data analysis: Use "Data Analysis and Insights Generator"
- For comparison frameworks: Use "Comparative Analysis Framework"
- For trend analysis: Use "Trend Analysis and Future Prediction"

### GitHub Automation (`prompts/tools/github.md`)
- For repository setup: Use "Repository Setup and Structure"
- For pull request reviews: Use "Pull Request Review Assistant"
- For GitHub Actions workflows: Use "GitHub Actions Workflow Creator"
- For issue management: Use "Issue Triage and Management Bot"

### Shell/Command Line Operations (`prompts/tools/shell.md`)
- For file operations: Use "Advanced File Operations Assistant"
- For system monitoring: Use "System Monitoring and Maintenance"
- For data processing: Use "Data Processing Pipeline"
- For development environment setup: Use "Development Environment Bootstrapper"

## PROMPT ADAPTATION GUIDELINES

When adapting a prompt template for a specific request:

1. **Replace all placeholders**: Any text in [BRACKETS] should be replaced with the user's specific information
2. **Maintain the structure**: Keep the original structure and sequence of the prompt
3. **Add context as needed**: Include relevant user context that may help with generating a better response
4. **Remove irrelevant sections**: If parts of the prompt are not applicable, they can be omitted
5. **Preserve instruction clarity**: Ensure the adapted prompt provides clear instructions

## PROMPT ENHANCEMENT

You may enhance the base prompts by including:

1. **System role context**: Define your operational mode (e.g., "You are an expert project manager...")
2. **Output format specification**: Explicitly state how the response should be structured
3. **Examples**: Include sample inputs and expected outputs when helpful
4. **Constraints**: Add any limitations or requirements specific to the user's context

## CROSS-REFERENCE MECHANISM

To handle complex requests that span multiple categories:

1. **Identify primary and secondary needs**: Determine the main category and any supporting categories
2. **Combine prompt elements**: Extract relevant parts from multiple prompts and integrate them coherently
3. **Maintain priority order**: Structure the combined prompt to address the primary need first
4. **Preserve consistency**: Ensure the combined prompt maintains a consistent voice and approach

## PROMPT SELECTION DECISION TREE

Use this decision flow to determine which prompt to apply:

1. Is the request about organizing tasks, time, or work?
   → Use Productivity Prompts

2. Is the request about writing, reviewing, or improving code?
   → Use Coding Prompts

3. Is the request about gathering, analyzing, or synthesizing information?
   → Use Research Prompts

4. Is the request about GitHub repository management or automation?
   → Use GitHub Prompts

5. Is the request about command-line operations or system administration?
   → Use Shell Prompts

## CONTINUOUS IMPROVEMENT PROTOCOL

When applying these prompts:

1. **Track effectiveness**: Note which prompts and adaptations produce the best results
2. **Identify gaps**: If a user request doesn't clearly match existing prompts, record this as a potential new prompt category
3. **Refine adaptations**: Improve placeholder replacements based on user feedback and results
4. **Suggest extensions**: If you identify potential improvements to existing prompts, document these suggestions

## EXAMPLES OF PROMPT APPLICATION

### Example 1: Daily Planning Request

User request: "I need help planning my day. I have these tasks: finish report, team meeting at 2pm, prepare presentation, and review budget."

AI response process:
1. Identify category: Productivity
2. Select prompt: "Daily Planning Assistant"
3. Adapt by replacing [LIST TASKS] with the user's specific tasks
4. Apply the adapted prompt to generate a structured daily plan

### Example 2: Code Refactoring Request

User request: "Can you help me improve this Python function? It works but it's messy: [code snippet]"

AI response process:
1. Identify category: Coding
2. Select prompt: "Code Refactoring Assistant" 
3. Adapt by replacing [PASTE CODE HERE] with the user's code snippet
4. Apply the adapted prompt to generate refactoring suggestions

## IMPLEMENTATION NOTES

- All prompts are designed to be platform-agnostic and should work across different AI systems
- The repository structure allows for easy navigation and prompt retrieval
- New prompts can be added to existing categories or new categories can be created as needed
- Always prioritize the user's specific needs over rigid adherence to prompt templates

By following these instructions, you'll be able to effectively utilize the structured prompts in this repository to provide consistent, high-quality assistance across a wide range of user requests.
