# automate-gh-release

A sample github action config which generate new release version automatically and following SemVer rule. Commits to master must have either "break"/"feat"/"fix" keyword to determine major/minor/patch version bump.

`PRIVATE_GITHUB_TOKEN` is added in github action secret to enable version bump triggering release workflow. This is because the default github-actions token cannot trigger new workflow automatically.