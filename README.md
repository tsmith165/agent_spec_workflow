# Agent Spec Workflow

A collection of prompts and markdown templates designed to enhance LLM task completion accuracy through structured specifications and workflows.

## Overview

This project provides a systematic approach to working with AI agents by establishing a clear specification process. It helps bridge the gap between human requirements and AI task execution by creating detailed, structured specifications that both humans and AI can understand and follow.

## Key Features

-   Standardized specification templates for different project types
-   Step-by-step workflow for creating and maintaining specs
-   Built-in review checkpoints with senior developers
-   Iterative improvement process
-   Clear rules and guidelines for AI agents

## Project Structure

```
agent_spec_workflow/
├── spec_templates/
│   ├── AGENT_SPEC_TEMPLATE-RUST_PLUGIN.md
│   └── AGENT_SPEC_TEMPLATE-NEXTJS_15.md
├── AGENT_SPEC-SETUP.md
├── AGENT_SPEC-START_POINT.md
├── UPDATE_SPEC_AND_CONTINUE.md
└── GO_TO_NEXT_STEPS.md
```

## Usage

1. **Setup**

    - Copy the appropriate template from `/spec_templates/` based on your project type
    - Rename it to `AGENT_SPEC_TEMPLATE.md` in your project root
    - Create a new spec file in `/specs/<TASK_NAME>/`

2. **Initial Specification**

    - Use `AGENT_SPEC-START_POINT.md` as your template
    - Fill in all required sections with task details
    - Send to the AI agent for spec creation

3. **Review & Implementation**
    - Review the generated spec with senior developers
    - Use `GO_TO_NEXT_STEPS.md` to proceed with implementation
    - Iterate and update using `UPDATE_SPEC_AND_CONTINUE.md`

## Best Practices

-   Keep specifications clear and concise
-   Document all assumptions and architectural decisions
-   Regular check-ins with senior developers
-   Maintain spec accuracy through continuous updates
-   Focus on simple solutions over complex abstractions

## Benefits

-   Improved AI task completion accuracy
-   Consistent documentation
-   Clear communication between humans and AI
-   Structured review process
-   Maintainable implementation steps

## Contributing

Feel free to submit issues and enhancement requests to improve the templates and workflow process.
