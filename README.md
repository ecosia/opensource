# Open source template

A template for open source packages. Catered for npm packages, but usable for all kinds of open source solutions.

## Usage

For now, bootstrapping of a new is a manual process, at least until it's ready to be used as [GitHub template](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template). Follow the steps:

1. Create a new public repository
2. Copy all files over
3. Replace this `README` with `README.template.md`
3. Fill in the `[placeholder]`s

### GitHub repository

Follow these extra recommendations to set up your repository for open source. Certain projects may need tweaks to these options. Feel free to carefully review and change them:

1. Settings:
    1. Options
        1. Features section
            1. Disable "Wikis" unless you plan to have a wiki section
            2. Make sure "Issues" is enabled, use them to communicate changes and updates with the community
            3. Disable "Projects" unless you plan to use a feature tracker
        2. Merge button: enable all options (merge commits, squash and rebasemerging, auto-merge and automatically delete head branches
    2. Security & analysis: enable all options (dependency graph, dependabot alerts, dependabot security updates)
    3. Branches: protect `main` branch as follow:
        1. Enable "Require pull request reviews before merging" with 1 approving review + Enabled "Dismiss stale pull request approvals when new commits are pushed"
        2. Enable "Require status checks to pass before merging" once your have a required check set up (e.g. CI workflow)
        3. Enabled "Restrict who can push to matching branches"
        4. Make sure "Allow force pushes" and "Allow deletions" are disabled
2. Insights
    1. Community: make sure all points are green, except for "Pull request template" as this template does not prescribe one

## Resources

- [Open Source Guides](https://opensource.guide)
