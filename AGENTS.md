# AI Coding Interview

This is a time-boxed 60-minute practical coding interview.

## Working Style
- Start with a brief plan, then build.
- Prioritize a small, correct, working solution before adding sophistication.
- Keep responses concise and action-oriented.
- Make changes in small, reviewable steps.
- Do not silently invent important requirements or assumptions.
- Surface important ambiguities so I can decide or clarify them.
- Alway ask before making any code changes.

## Code Quality
- Prefer simple, readable, maintainable code.
- Use clear names and focused functions or classes.
- Avoid unnecessary abstractions, design patterns, and dependencies.
- Add error handling where it materially affects correctness.
- Preserve existing behavior unless a new requirement explicitly changes it.

## Testing
- Alway ask before running any test.
- Add focused pytest tests for important behavior and edge cases.
- Validate changes frequently without running unnecessary tests.
- Prefer targeted tests during iteration.
- Run the full test suite after larger changes and before finalizing.
- Use `python -m pytest` when running the full test suite.

## Iteration
- After the basic happy path works, identify the highest-value edge cases or extensions.
- Before a substantial refactor, briefly explain why it is useful.
- When reviewing code, prioritize correctness and architectural issues over cosmetic changes.
- If time is limited, favor working functionality and high-impact fixes over polish.