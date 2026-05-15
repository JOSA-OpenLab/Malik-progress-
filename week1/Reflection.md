#  Git Archaeology Reflection
The commit points to a tree object, which represents the project’s directory at that exact moment, and that tree in turn links to blobs that store the actual file contents. Instead of saving full copies of files each time, Git breaks everything into these reusable objects connected by SHA-1 hashes, which makes the history both efficient and traceable. The parent field also showed how commits are linked in a chain, forming the project’s history


# Reflog Rescue Drill
![alt text](image.png)
![alt text](image-1.png)


# Commit History Refactor

In this task, I cleaned and reorganized my Git commit history using interactive rebase.

## What I Did
- Squashed unnecessary commits into a single clean commit
- Rewrote commit messages to follow Conventional Commits style
- Reordered commits to improve the history flow and readability
- Verified the final history using `git log`

