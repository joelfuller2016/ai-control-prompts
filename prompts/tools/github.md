# GitHub Automation Prompts

These prompts are designed to help you use AI to control and automate GitHub-related tasks.

### Title: Repository Setup and Structure
**Tags**: github, repository-setup, project-structure, automation  
**Prompt**: "Create a new GitHub repository named `[REPO_NAME]` with the following structure and initial files:

1. Initialize the repository with a README.md that explains the purpose: '[PURPOSE_DESCRIPTION]'
2. Create the following folder structure:
```
[FOLDER_STRUCTURE]
```
3. Add a LICENSE file with [LICENSE_TYPE] (e.g., MIT, Apache 2.0)
4. Create a .gitignore file appropriate for [LANGUAGE/FRAMEWORK]
5. Set up initial configuration files for [CI/CD_TOOL] if applicable
6. Create issue templates for: bug reports, feature requests, and documentation updates
7. Add a CONTRIBUTING.md file with contribution guidelines
8. Set up branch protection rules for the main branch

After creating the repository and adding these files, provide me with the repository URL and a summary of what was created."

### Title: Pull Request Review Assistant
**Tags**: github, code-review, pull-request, quality-assurance  
**Prompt**: "I need help reviewing the following GitHub pull request:

PR Title: [PR_TITLE]
Repository: [REPO_NAME]
PR URL or number: [PR_URL_OR_NUMBER]

Please conduct a thorough review that:

1. Analyzes code quality, readability, and adherence to best practices
2. Identifies potential bugs, edge cases, or performance issues
3. Checks for security vulnerabilities or antipatterns
4. Verifies test coverage and test quality
5. Ensures documentation is updated appropriately
6. Confirms the changes align with the PR description and requirements
7. Suggests specific improvements with code examples where applicable
8. Provides an overall assessment: approve, request changes, or comment

Format your review as it would appear in GitHub comments, with code blocks and line references where appropriate."

### Title: GitHub Actions Workflow Creator
**Tags**: github, github-actions, ci-cd, automation  
**Prompt**: "I need to create a GitHub Actions workflow for [PROJECT_TYPE] that accomplishes the following tasks:

1. Triggers on: [TRIGGER_EVENTS] (e.g., push to main, pull requests, etc.)
2. Sets up the environment with: [ENVIRONMENT_REQUIREMENTS]
3. Performs these steps in order:
   - [STEP_1_DESCRIPTION]
   - [STEP_2_DESCRIPTION]
   - etc.
4. Includes appropriate error handling and notifications
5. Implements caching for faster builds where applicable
6. Uses secrets for sensitive information
7. Optimizes for performance and reliability

Please create a complete GitHub Actions workflow file (.github/workflows/workflow-name.yml) with appropriate YAML formatting and comments explaining each section. Include any setup or configuration steps I'll need to take in my repository settings."

### Title: Issue Triage and Management Bot
**Tags**: github, issue-management, project-management, automation  
**Prompt**: "I need you to help me set up a system for triaging and managing GitHub issues in our repository. Create a comprehensive plan that includes:

1. A GitHub Actions workflow that automatically:
   - Labels new issues based on their content and templates used
   - Assigns issues to team members based on expertise areas
   - Adds issues to appropriate project boards
   - Requests more information when issues are incomplete
   - Identifies and flags potential duplicates

2. Issue templates for:
   - Bug reports (with standardized reproduction steps)
   - Feature requests (with impact and value sections)
   - Documentation improvements
   - Performance issues

3. A set of label definitions and color scheme for our repository that covers:
   - Priority levels
   - Type categories
   - Status indicators
   - Component/module identifiers
   - Effort estimation

4. A commenting strategy for the bot to use when interacting with issue creators and maintainers

5. Example GitHub CLI or API commands I can use to bulk-update existing issues to this new system

Please provide all necessary files, scripts, and instructions for implementing this system in our repository."
