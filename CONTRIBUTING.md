# Contributing

We appreciate all kinds of contributions. As a contributor, here are the guidelines we would like you to follow:

 - [Issues and Bugs](#issue)
 - [Feature Requests](#feature)
 - [Submission Guidelines](#submit-pr)
 - [Coding Rules](#rules)
 - [Commit Message Guidelines](#commit)
 - [Public/Business Package](#public-business)

## <a name="issue"></a> Found an Issue?
If you find a bug in the source code or a mistake in the documentation, you can help us by
[submitting an issue](#submit-issue) to our [GitHub Repository][github]. Including an issue 
reproduction (via StackBlitz, JsBin, Plunkr, etc.) is the absolute best way to help the team quickly
diagnose the problem. Screenshots are also helpful.

You can help the team even more and [submit a Pull Request](#submit-pr) with a fix.


## <a name="feature"></a> Want a Feature?
You can *request* a new feature by [submitting an issue](#submit-issue) to our [GitHub
Repository][github]. If you would like to *implement* a new feature, please submit an issue with
a proposal for your work first, to be sure that we can use it. 
Please consider what kind of change it is:

* For a **Major Feature**, first open an issue and outline your proposal so that it can be
discussed. This will also allow us to better coordinate our efforts, prevent duplication of work,
and help you to craft the change so that it is successfully accepted into the project.
* **Small Features** can be crafted and directly [submitted as a Pull Request](#submit-pr).


### <a name="submit-issue"></a> Submitting an Issue
If your issue appears to be a bug, and hasn't been reported, open a new issue.
Providing the following information will increase the
chances of your issue being dealt with quickly:

* **TODO** - TODO

You can file new issues by providing the above information [here](https://github.com/sbb-design-systems/sbb-design-system/issues/new/choose).


### <a name="submit-pr"></a> Submitting a Pull Request (PR)
See [PROCESS.md](https://github.com/sbb-design-systems/sbb-design-system/blob/master/PROCESS.md)


## <a name="commit"></a> Commit Message Guidelines

This project uses [Conventional Commits](https://www.conventionalcommits.org/) to generate the changelog.

### Commit Message Format
```
<type>(<optional scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

Any line of the commit message cannot be longer 100 characters! This allows the message to be easier
to read on GitHub as well as in various git tools.

### Type
Must be one of the following:

* **feat**: A new feature
* **fix**: A bug fix
* **docs**: Documentation only changes

### Scope
The scope could be anything specifying place of the commit change. For example
`website`, `webapp`, `mobile`, etc.

### Subject
The subject contains succinct description of the change:

* use the imperative, present tense: "change" not "changed" nor "changes"
* don't capitalize first letter
* no dot (.) at the end

### Body
Just as in the **subject**, use the imperative, present tense: "change" not "changed" nor "changes".
The body should include the motivation for the change and contrast this with previous behavior.

### Footer
The footer should contain any information about **Breaking Changes** and is also the place to
reference GitHub issues that this commit **Closes**.

**Breaking Changes** should start with the word `BREAKING CHANGE:` with a space or two newlines.
The rest of the commit message is then used for this.
