# Code Comprehension Quiz

A Claude skill that automatically generates multiple-choice quizzes to test your understanding of code changes and explanations.

## Installation

```bash
npx skills add https://github.com/Haroutkhac/code-comprehension-quiz
```

## When It Triggers

The skill activates automatically after:
- Writing or modifying code (new functions, refactors, bug fixes)
- Explaining code patterns, architecture, or concepts
- Debugging sessions with root cause analysis
- Any response containing an "Insight" block

## Features

- **Adaptive difficulty**: 2-5 questions based on complexity
- **Deep understanding focus**: Tests tradeoffs, failure modes, alternatives—not surface-level recall
- **Randomized answers**: Prevents pattern-based guessing
- **Detailed review**: Explains correct answers and misconceptions

## Question Types

Questions focus on deeper understanding:
- Tradeoff analysis
- Failure modes
- Alternative reasoning
- Implication chains
- Root cause analysis
- Edge cases

## Example

After fixing a race condition:

```
Question: The cleanup function prevents the bug by:

A) Cancelling the HTTP request before it completes
B) Resetting the component state to initial values
C) Ignoring stale responses from superseded requests
D) Blocking concurrent effect executions
```

## License

MIT
