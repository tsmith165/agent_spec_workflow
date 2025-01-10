# Agent SPEC Setup Steps

1. Copy the spec template related to your project from `/spec_templates/` to the root of the project you are working on
2. Rename the file to `AGENT_SPEC_TEMPLATE.md`
3. Create a new markdown file with the format `<TASK_NAME>-SPEC.md` in the `/specs/<TASK_NAME>/` directory
4. Utilize the `AGENT_SPEC-START_POINT.md` as a template for your initial message to the AI agent
    - Fill in all sections with all details required for the task
    - Replace the `TASK_NAME` in `/specs/<TASK_NAME>/<TASK_NAME>-SPEC.md` with the actual task name
5. Send the message to the AI agent and wait for the spec to be created
6. Review the spec and make any necessary changes
7. Once the spec is approved, send the `GO_TO_NEXT_STEPS.md` message to the AI agent
8. Once the agent completes it's attempt at the changes, review the changes and repeat the process until the task is complete
