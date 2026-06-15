# agenticDeveloper

## This would be like an H2

### Like and H3

**Testing Bold**

# RUN ACTION

## Pull Requests

Pull Requests (PRs) are a way to propose changes to the codebase. They allow you to collaborate with others, review code, and merge changes into the main branch.

### How to Create a Pull Request

1. **Fork or branch the repository** – Create a new branch from `main` (or another base branch) for your changes:
   ```bash
   git checkout -b my-feature-branch
   ```

2. **Make your changes** – Edit files, add new features, or fix bugs on your branch.

3. **Commit your changes** – Stage and commit your work with a clear message:
   ```bash
   git add .
   git commit -m "Add my new feature"
   ```

4. **Push your branch** – Push the branch to the remote repository:
   ```bash
   git push origin my-feature-branch
   ```

5. **Open a Pull Request** – Go to the repository on GitHub, click **"Compare & pull request"**, fill in a title and description, and submit.

### Pull Request Best Practices

- **Write a clear title and description** – Explain what the PR does and why.
- **Keep PRs small and focused** – Smaller changes are easier to review and less likely to introduce bugs.
- **Link related issues** – Reference issues in the description using `Closes #<issue-number>` to automatically close them when the PR is merged.
- **Request reviewers** – Assign team members to review your code before merging.
- **Respond to feedback** – Address review comments by pushing additional commits or discussing the changes.
- **Ensure checks pass** – Make sure all CI/CD checks (tests, linters, etc.) pass before requesting a merge.

### Merging a Pull Request

Once your PR has been approved and all checks pass, it can be merged into the target branch. GitHub offers three merge strategies:

- **Merge commit** – Preserves all commits from the branch with a merge commit.
- **Squash and merge** – Combines all commits into a single commit for a cleaner history.
- **Rebase and merge** – Replays commits on top of the base branch without a merge commit.
