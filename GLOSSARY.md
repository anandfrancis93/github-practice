# GitHub Glossary

**Repository** — a project folder that GitHub stores and version-controls.

**Commit** — a saved snapshot of your files, with a message explaining why.

**Branch** — a separate line of work, so you can change things without touching main.

**Diff** — the difference between two versions. Minus means old, plus means new.

**Pull request** — a proposal to merge one branch into another, with room for review.

**Merge** — combining the changes from one branch into another.

**Clone** — making the first local copy of a GitHub repository on your computer.

**Push** — uploading your local commits to GitHub.

**Pull** — downloading other people's commits from GitHub into your local copy.

**Fork** — your own copy of someone else's repository, stored under your account, so you can change it without needing their permission.

**Origin** — the default nickname for the GitHub copy of your repository. When you push or pull without naming a destination, this is where it goes.

**Staging area** — a full snapshot of what your next commit would contain, pre-filled as a copy of the last commit. It is never empty. `git add` edits it; editing a file does not. Also called the **index**, or the **cache** in older flags.

**Detached HEAD** — the state where you have moved to a specific commit rather than a branch. Any commit you make here belongs to no branch and is easy to lose.

**Upstream** — the branch on a remote that your local branch is paired with. Stored as two lines in `.git/config`, and used to answer "push where?" and "how far ahead or behind am I?". It is a saved default, not a live connection.

**Remote-tracking branch** — your local note of where a remote's branch was the last time you looked, such as `origin/main`. It only updates when you fetch, pull, or push.

**Merge base** — the most recent commit that two branches both share. Git finds it by walking backwards from each branch until the paths meet, then compares each side against it to work out what each actually changed.
