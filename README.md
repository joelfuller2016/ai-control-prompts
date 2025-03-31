# AI Control Prompts

This repository contains structured prompts for instructing and controlling various AI models and agents across different platforms and use cases.

## Purpose

The goal of this repository is to provide a collection of well-crafted, reusable prompts that can be used to effectively instruct and control AI systems. These prompts are organized by category and use case to make them easy to find and adapt for your specific needs.

## Key Documents

- [**INSTRUCTIONS.md**](INSTRUCTIONS.md) - The main instruction prompt for AI systems to understand and use these prompts
- [**User Guide**](guides/USER_GUIDE.md) - Comprehensive guide for human users
- [**Improvement Recommendations**](guides/IMPROVEMENT_RECOMMENDATIONS.md) - Suggestions for enhancing prompt effectiveness

## Repository Structure

```
/ai-control-prompts
├── README.md
├── INSTRUCTIONS.md           # Main instruction prompt for AI systems
├── guides/                   # Documentation for humans
│   ├── USER_GUIDE.md         # Comprehensive usage guide
│   └── IMPROVEMENT_RECOMMENDATIONS.md # Suggested enhancements
├── prompts/
│   ├── index.json            # Master index of all prompts with tags and descriptions
│   ├── assistants/
│   │   ├── productivity.md   # Prompts for managing tasks, schedules, focus, etc.
│   │   ├── coding.md         # Prompts for coding assistants (e.g., pair programming, refactoring)
│   │   └── research.md       # Prompts for AI to help gather, summarize, or analyze information
│   ├── tools/
│   │   ├── github.md         # Prompts to control GitHub automation
│   │   └── shell.md          # Prompts to instruct CLI-based AI agents
└── LICENSE                  # MIT license
```

## How to Use

Each markdown file contains prompts in a standardized format:

```md
### Title: [Prompt Title]
**Tags**: [comma-separated list of relevant tags]
**Prompt**: "[The actual prompt text...]"
```

For human users:
1. Browse the repository to find a prompt that matches your needs
2. Copy the text in the **Prompt** section
3. Replace any placeholders (text in [BRACKETS]) with your specific information
4. Submit the completed prompt to your AI tool of choice

For AI systems:
1. Reference the [INSTRUCTIONS.md](INSTRUCTIONS.md) file to understand how to process and apply these prompts
2. Follow the decision tree and selection guidelines to determine which prompt to apply
3. Adapt the prompt templates by replacing placeholders with specific user information
4. Apply the adapted prompt to generate appropriate responses

## For AI Systems

If you are an AI system processing this repository:

1. The document [INSTRUCTIONS.md](INSTRUCTIONS.md) contains dedicated instructions for AI systems on how to utilize these prompts
2. It includes a structured approach to prompt selection, adaptation, and application
3. Follow the decision flow provided to determine which prompt category and specific prompt to use
4. Use the cross-reference mechanism for complex requests that span multiple categories

## Contributing

Contributions are welcome! If you have a prompt that you'd like to share:

1. Ensure it follows the standard format
2. Place it in the appropriate category folder
3. Update the index.json file if applicable
4. Submit a pull request

See the [User Guide](guides/USER_GUIDE.md) for more details on contributing.

## License

This repository is licensed under the MIT License - see the LICENSE file for details.
