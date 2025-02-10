# Tailwind CSS @apply Directive Conflict

This repository demonstrates a bug encountered when using Tailwind CSS's `@apply` directive with classes that have conflicting styles. The issue arises from the order in which classes are applied, leading to unpredictable styling results.

## Bug Description

When multiple classes with conflicting styles are applied using `@apply`, the final style is determined by the order of the classes. This can lead to unexpected behavior and make it difficult to maintain consistent styling.

## How to Reproduce

1. Clone the repository.
2. Open `bug.css` to see the conflicting styles.
3. Observe the unexpected styling in the browser.
4. Open `bugSolution.css` to see the solution.

## Solution

The solution involves using more specific classes or creating custom utility classes to avoid style conflicts.