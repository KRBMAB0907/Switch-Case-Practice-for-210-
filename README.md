# Switch Mystery Practice

A self-grading practice quiz for tracing Java `switch` statements (CS1 / Programming Principles I).

It has three problems with 15 method calls in total. They cover:

- fall-through when a case has no `break`
- stacked cases such as `case 'a': case 'e':`
- `return` inside a case compared with `break`
- `default` reached directly or by falling through
- Java's `%` with negative numbers

## Use it

Open `index.html` in any browser. It's a single file with no build step.

To host it with **GitHub Pages**:

1. Push `index.html` to your repo.
2. Go to **Settings → Pages** and set the source to your main branch, using the `/ (root)` folder.

## Adding problems

All problems live in the `PROBLEMS` array near the bottom of `index.html`. Each call is written as `[call, expectedAnswer, explanation]`.
