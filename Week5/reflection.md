# Build a real workflow  
For this task, I added a GitHub Actions CI workflow to my repository using .github/workflows/ci.yml. It includes linting, testing, a matrix for multiple versions, and caching to improve performance. I also added a status badge to the README to show the build status. This helped me learn how to automate testing and code quality checks using CI.[REPO](https://github.com/Malik740/GYMFlow)

# Run it with act
I used act to run the GitHub Actions workflow locally before pushing it:
```YAML
act push -W .github/workflows/main.yml -j <job-name>
```
act executed the workflow inside a Docker environment, including dependency installation and full job validation. Initially, I encountered an issue because I was in the wrong directory (GYM-System.tsets), where the .github/workflows path did not exist. After switching to the correct project root, act successfully detected and ran the workflow.

During setup, act also prompted me to choose a default image size, and I selected Medium to ensure a balanced environment for running the jobs.