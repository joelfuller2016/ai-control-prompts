# Shell Automation Prompts

These prompts are designed to help you use AI to control and automate command-line tasks across various operating systems.

### Title: Advanced File Operations Assistant
**Tags**: shell, file-management, automation, batch-processing  
**Prompt**: "I need to perform a series of file operations on my [OPERATING_SYSTEM] system. Act as my command-line expert and help me with the following tasks:

1. I need to find all files with the extension [EXTENSION] in the directory [DIRECTORY] and its subdirectories that:
   - Were modified in the last [TIME_PERIOD] (e.g., 7 days)
   - Contain the text pattern [PATTERN]
   - Are larger than [SIZE]

2. For each matching file, I need to:
   - Create a backup copy with a timestamp in the filename
   - Perform a search and replace operation to change [OLD_TEXT] to [NEW_TEXT]
   - Update the file permissions to [PERMISSIONS]

3. Finally, I need to:
   - Generate a log file with the list of all modified files
   - Create a summary report showing how many files were changed and any errors encountered

For each step, provide the exact commands I should run, with explanations of what each option does and any potential issues to watch out for. If certain operations are risky, suggest safer alternatives."

### Title: System Monitoring and Maintenance
**Tags**: shell, system-admin, monitoring, maintenance  
**Prompt**: "I need to set up a comprehensive system monitoring and maintenance script for my [OPERATING_SYSTEM] server. Create a shell script that performs the following tasks:

1. System Health Checks:
   - CPU, memory, and disk usage monitoring
   - Process monitoring for critical services
   - Network connection status and traffic analysis
   - Log file scanning for critical errors or suspicious activity

2. Automated Maintenance:
   - Clean up temporary files and caches based on configurable thresholds
   - Back up critical configuration files before any changes
   - Update system packages with proper error handling and rollback capability
   - Rotate and compress log files to prevent disk space issues

3. Reporting and Alerts:
   - Generate a daily summary report of system status
   - Send alerts via email or other notification methods when thresholds are exceeded
   - Log all maintenance activities with timestamps and results
   - Store historical performance data for trend analysis

The script should be well-commented, include error handling, and be designed to run as a cron job. Include configuration variables at the top of the script for easy customization."

### Title: Data Processing Pipeline
**Tags**: shell, data-processing, ETL, automation  
**Prompt**: "I need to create a shell-based data processing pipeline that performs the following ETL (Extract, Transform, Load) operations:

1. Extract phase:
   - Download files from [SOURCE] (could be an API, FTP server, or other data source)
   - Validate the downloaded files for integrity and completeness
   - Extract data from multiple file formats (CSV, JSON, XML, etc.)

2. Transform phase:
   - Clean the data (remove duplicates, handle missing values, correct formatting issues)
   - Apply transformations using tools like awk, sed, grep, or jq
   - Perform calculations or aggregations on the data
   - Join or merge data from multiple sources

3. Load phase:
   - Format the data for the target system ([TARGET_SYSTEM])
   - Upload or insert the processed data
   - Verify the data was correctly loaded
   - Archive the processed files and generate processing logs

Design this pipeline to be robust (with error handling and retry logic), efficient (using appropriate tools and optimizations), and maintainable (with clear documentation and modular design). Provide the complete shell script with comments explaining each section."

### Title: Development Environment Bootstrapper
**Tags**: shell, development-environment, setup, configuration  
**Prompt**: "I need to create a shell script that will set up a complete development environment for [PROGRAMMING_LANGUAGE/FRAMEWORK] development on a fresh [OPERATING_SYSTEM] installation. The script should perform the following tasks:

1. System Preparation:
   - Install necessary system packages and dependencies
   - Configure system settings for development (e.g., increasing file watchers, etc.)
   - Set up the appropriate environment variables

2. Development Tools Installation:
   - Install the correct versions of [LANGUAGE/FRAMEWORK] and its runtime
   - Install package managers, build tools, and other utilities
   - Set up version management tools if applicable
   - Install and configure the recommended IDE or code editor with extensions

3. Project Scaffolding:
   - Create a standard directory structure for new projects
   - Initialize version control
   - Set up testing frameworks and linters with configuration files
   - Install common libraries and dependencies
   - Create template files (README, .gitignore, etc.)

4. Local Development Services:
   - Set up local databases or other required services
   - Configure local development servers
   - Set up containerization tools if needed

The script should be idempotent (safe to run multiple times), include user prompts for customizable options, and provide clear output about what's happening at each step. Include validation checks to ensure each component is correctly installed."
