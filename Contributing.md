# Contributing

First and foremost, thanks for the help, I appreciate all of the contributions, and the awesome-zsh-plugins list wouldn't be nearly as complete without them. You may add to the list by submitting a pull request or adding a link in an issue.

## Entry Guidelines

### General

* Please make sure all new framework, plugin, themes or completions entries have a license file. Some users are particular about the code they use and want to be sure they are compliant with licensing, so please make sure it's easy for them to determine what the license is. I am aware that there are existing entries without licenses, they were added before I instituted the license policy.
* Descriptions should be clear, concise, and non-promotional.
* The list is split into sections for frameworks, plugins, themes and completions, please add your entries to the appropriate section(s). If an entry is a plugin that provides both plugin functionality and tab completions, add it to the plugins section. If an entry is a plugin that provides both plugin functionality and a theme, please add it to the theme section. The completions section is meant for projects that only provide extra tab completions.
* Descriptions should follow the link, on the same line, with capitalization consistent with the other entries in the section.
* Each entry should be a single line that ends in a period. This makes keeping the sections sorted easier. We let GitHub's markdown formatter handle adding any required line breaks rather than embedding breaks in the entries ourselves, this also allows us to work with any browser window width.
* For consistency, please use all caps for ZSH in all entry descriptions.
* Each entry should be limited to one link, and that link should be the first part of the line. It is ok to submit more than one entry in a PR.
* Please make sure all framework, plugin, themes or completions list entries are sorted *alphabetically*.
* The link should be named the name of the package or project.
* Your PR should pass the CircleCI checks. If the checks show an error that you didn't add (a previous plugin entry has gone 404, for example) you don't _have_ to fix those errors, though I'll certainly appreciate the help if you do, or if you create an issue documenting the problem so I can fix it.

### Themes

* If you're submitting a theme, please make sure that the theme repo has a screen shot so that list users can tell what it looks like before installing it.
* It is fine to have multiple new entries in a single PR.
* No need to squash commits. It is fine to have multiple commits in a PR.

## To remove an entry:

Open an issue to discuss why the entry should be removed, and optionally create a PR.

Entries that have gone 404 do not require an issue to remove - just make a PR.
