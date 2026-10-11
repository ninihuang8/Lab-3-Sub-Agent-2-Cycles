# Innovation and Disruption Agent
Initial version 0.1-student; responses not generated and analytical performance not yet tested.

Use the frozen tools from the scaffold root:
1. Run `python tools/check_frozen_core.py`.
2. Build a packet with `python tools/build_prompt.py --agent agents/innovation_disruption_agent --case agents/innovation_disruption_agent/cases/primary.json` (repeat for contrasts).
3. Run in ChatGPT; preserve JSON in responses/ with case and instruction version in the filename.
4. Run `python tools/validate_response.py <response>` and separately inspect full output-schema compliance, evidence, three-level reasoning, and counterarguments.
5. Preserve a real weakness, revise specialist instructions, and rerun unchanged cases. Never overwrite initial evidence.

Initial instructions are preserved in records/specialist_instructions_v0.1.md. Combined records/agent_record.md covers template sections A–E, evidence, testing, revisions, and handoff. Self-reflection awaits the student's observations after testing. No API key is required. No GitHub repository/branch/commit is claimed.
