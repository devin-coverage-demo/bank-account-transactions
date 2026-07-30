# Agent conventions

## Testing standards
- Tests must assert on behaviour, not merely that code executed
- A test that would pass regardless of whether the code under test is correct
  is not acceptable and should be removed
- Prioritise error handling branches and input validation over happy paths
- Follow existing test conventions in this repo where any exist

## Scope
- Work only within the paths named in the task
- Do not modify production source code to make a test pass
- Do not modify existing tests unless the task says so

## PR format
- Conventional commits: type(scope): message
- The PR description states coverage before and after
- List anything you were uncertain about
