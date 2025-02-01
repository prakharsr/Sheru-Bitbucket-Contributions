# Sheru Bitbucket Contributions

I imported my private bitbucket contributions from 37+ repositories in Sheru into this mock repository on github to update the contribution chart. 
- The date and time of contributions is the same without any modification.
- The repo names have been hidden for privacy.
- The commit messages have been hidden for privacy.
- The content of the commits are hidden for privacy.

Used this github repo for this task - https://github.com/miromannino/Contributions-Importer-For-Github

The command used was:

```
git-import-contributions repo \
    --repos <repo names> \
    --mock_repo <mock repo name> \
    --author prakhar.s@sheru.se
```

**This is a mock repository.** 

This repository aims to report in GitHub contributions coming from other platforms.

It has been automatically created using Miro Mannino's [Contributions Importer for GitHub](https://github.com/miromannino/contributions-importer-for-github)

## Notice

The content of this repository contains mock code. This prevents private source code from being leaked. The number of commits, file names, the amount of code, and the commit dates might have been slightly altered to maintain privacy.

Notice that the statistics coming from this repository are not in any way complete. Commits only come from other selected git repositories. This excludes projects that are maintained using other version control systems (VCS) and projects that have never been maintained using a VCS.

## Reasons

GitHub shows contributions statistics of its users. There are [several reasons](https://github.com/isaacs/github/issues/627) why this feature could be debatable.

Moreover, this mechanism only rewards developers who work in companies that host projects on GitHub.
Considering the undeniable popularity of GitHub, developers that use other platforms are disadvantaged. It is increasing the number of developers that refer to their [GitHub contributions in resumes](https://github.com/resume/resume.github.com). Similarly, recruiters [may use GitHub to find talent](https://www.socialtalent.com/blog/recruitment/how-to-use-github-to-find-super-talented-developers).

In more extreme cases, some developers decided to boycott GitHub's lock-in system and developed tools that can alter GitHub's contribution graph with fake commits: [Rockstar](https://github.com/avinassh/rockstar) and [Vanity text for GitHub](https://github.com/ihabunek/github-vanity) are good examples.

Instead, [Contributions Importer for GitHub](https://github.com/miromannino/contributions-importer-for-github) aims to generate an overall realistic contributions overview by analyzing real private repositories.

