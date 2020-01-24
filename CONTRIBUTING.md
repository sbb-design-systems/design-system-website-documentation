# Contributing

We appreciate all kinds of contributions. As a contributor, here are the guidelines we would like you to follow:

 - [Issues and Bugs](#issue)
 - [Feature Requests](#feature)
 - [Submission Guidelines](#submit-changes)
 - [Commit Message Guidelines](#commit)

## <a name="issue"></a> Found an Issue?
If you find a bug in the design system documentation or a mistake in the sketch library file, you can help us by
[submitting an issue](#submit-issue) to our [GitHub Repository][github]. Including an issue reproduction is the
absolute best way to help the team quickly diagnose the problem. Screenshots are also helpful.


## <a name="feature"></a> Want a new Feature?
You can *request* a new feature (new component, module or a new characteristic of one of them) by
[submitting an issue](#submit-issue) to our [GitHub Repository][github]. 


## <a name="submit-issue"></a> Submitting an Issue
If your issue appears to be a bug or a new feature, and hasn't been reported, open a new issue.
You can file new issues by providing the above information [here](https://github.com/sbb-design-systems/design-system-website-documentation/issues/new/choose).


## <a name="submit-changes"></a> Submitting some changes
See [PROCESS.md](https://github.com/sbb-design-systems/design-system-website-documentation/blob/master/PROCESS.md)

## <a name="commit"></a> Commit Message Guidelines
This project uses [Conventional Commits](https://www.conventionalcommits.org/) to generate the changelog.

### Commit Message Format
```
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

Any line of the commit message cannot be longer than 100 characters! This allows the message to be easier
to read on GitHub as well as in various git tools.

### Type
Must be one of the following:

* **feat**: A new feature
* **fix**: A bug fix
* **docs**: Documentation only changes

### Scope
The scope could be anything specifying place of the commit change. For example
`website`, `webapp`, `mobile`

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

**Close issue**. Want to close some issue with the commit use the word `Closes` with a space and the issue number (e.g. Closes #39).