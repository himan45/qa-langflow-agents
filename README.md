QA Langflow Agents

Import any flow into Langflow: **Projects → New Flow → Import**, then select the JSON file from `flows/`.

- `bug_triage_agent.json` — triages Jira issues into severity/priority/next steps
- `flaky_test_agent.json` — compares two Playwright runs to separate flaky vs. reproducible failures
- `test_plan_test_case_generator.json` — chains a test plan generator into a test case generator
- `rca_bot.json` — produces structured Root Cause Analysis from incident descriptions

Requires a Groq API key set as a Langflow global variable named `GROQ_API_KEY` (or fill it in per-flow after import)
