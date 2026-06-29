#  Self-review
I reviewed one of my previous PRs that was not merged. The change I made to the ls page was technically correct, but it went against the purpose of the TLDR project, which is to keep commands easy to understand. I removed explanations for abbreviations, making the page less beginner-friendly. If I reviewed this PR today, I would suggest keeping those explanations. This taught me that a good change should support the project's goals, not just improve the code.[PR](https://github.com/tldr-pages/tldr/pull/22596)

# Two real reviews
## First one:
[PR](https://github.com/Asabeneh/30-Days-Of-Python/pull/859/changes)
The main idea of this change seems to be helping beginners understand how continue works in Python by showing what the next number should be and what it would be after the continue.
To improve clarity for learners, I suggest adding a short explanation of the logic behind the sequence, especially why certain numbers are skipped (for example, the jump when value = 3).
Right now, the transition between values is not clearly explained. It would be helpful to either:

add a brief comment explaining the jump from 3 to 4 when it occurs, or
include a small note describing the reasoning behind skipping values.
Alternatively, if this change adds confusion, it might be better to simplify or revert it and reintroduce it with a clearer educational explanation.