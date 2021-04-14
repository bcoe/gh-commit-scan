# GH Commit Scan

Scan the commits for a given repository.

## Usage

1. fetch a [personal access token](https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token) from GitHub.
2. install the tool from npm, `npm i gh-commit-scan -g`.
3. run the tool thusly:
    ```
    gh-commit-scan --token=abc123 github-project/github-repo
    ```

GH Commit Scan will open commits in your default browser:

1. 👀 eyeball the commit, looking for anything out of the ordinary.
2. go back to the CLI and indicate whether or not the commit was suspicious.
