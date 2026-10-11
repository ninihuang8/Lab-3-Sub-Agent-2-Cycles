# Innovation and Disruption Agent

Active version: 0.2-student. Three v0.1 tests, three v0.2 retests, and one supplementary test are complete. These session-based reasoning tests do not establish independent reproducibility or deployment performance.

Use the frozen tools from the scaffold root:
1. Run `python tools/check_frozen_core.py`.
2. Build a packet with `python tools/build_prompt.py --agent agents/innovation_disruption_agent --case agents/innovation_disruption_agent/cases/primary.json` (repeat for contrasts).
3. Run in ChatGPT; preserve JSON in responses/ with case and instruction version in the filename.
4. Run `python tools/validate_response.py <response>` and separately inspect full output-schema compliance, evidence, three-level reasoning, and counterarguments.
5. Preserve actual initial outputs and weaknesses before revising instructions and retesting. Never overwrite prior test evidence.

Preserved instruction snapshots, evidence, revision and comparison records are available in records/. The completed Agent Record covers sections A–F, including approved Self-Reflection and AI-assistance disclosure. No API key is required.

Repository: https://github.com/ninihuang8/Lab-3-Sub-Agent-2-Cycles
Branch: assignment-3-innovation-disruption-agent
Tested-artifact preservation commit: 0e3187d94d66182650b2b8d30c1a359caa531288
