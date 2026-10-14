Global Configuration: Using the --global flag sets your credentials system-wide, preventing the need to re-configure them for individual repositories.

Hidden Files: Standard directory listings hide dotfiles like .git, which require the ls -a command to display.

Tracked Files: Git identifies three directories for tracking, each containing user-created files.

Directory State: Untracked folders like .venv/ remain hidden and unaffected, leaving the newly created .gitignore as the sole addition.

Ignoring Files: Committing .gitignore enforces file-exclusion rules, preventing temporary or build artifacts from being shared with collaborators.

Staging Area: Staging a file transitions it from "untracked" status in the working directory to "changes to be committed."

Committing Changes: Committing records changes to the main history line, logging a descriptive message alongside the total number of modified files.

Commit Hashes: Short commit hashes serve as unique, abbreviated identifiers for tracking specific commits.

Standard Workflow: The core Git workflow follows a four-step cycle: editing files, checking status (git status), staging (git add), and committing (git commit).

Repository Landing Page: GitHub automatically renders a root-level README.md file as the primary project landing page.

Credential Caching: Secure token caching eliminates the need for repeated manual authentication during remote operations.

File Structure View: The remote repository view organizes primary project assets, including directories, configuration files, and documentation.

Pushing Commits: Pushing uploads local commits to GitHub without altering your local branch history.

Visibility & Storage: Private GitHub repositories limit cloud access to authorized users, whereas unpushed repositories exist solely on your local machine.