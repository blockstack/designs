# Contributing to Blockstack Designs

Looking to contribute something to Blockstack? **Here's how you can help.**

Please take a moment to review this document in order to make the contribution process easy and effective for everyone in the community.

Following these guidelines helps to communicate that you respect the time of everyone involved in the Blockstack open source community. In return, the community will address your issue or assess patches and features as quickly as possible.

## Table of contents

- [Open Source Design & design process](https://github.com/blockstack/designs/issues/267)
- [BlockstackDS (Design System) › Visit the repository](https://github.com/blockstack/design-system/issues/3)
- [Finding opportunities to contribute](#finding-opportunities-to-contribute)
- [Filenaming & directory structure](#filenaming--directory-structure)
- [Install & Setup Git LFS](#install--setup-git-lfs)
- [Using the issue tracker](#using-the-issue-tracker)
- [Bug reports](#bug-reports)
- [Feature requests](#feature-requests)
- [Pull requests](#pull-requests)
- [Code guidelines](#code-guidelines)
- [Maintainers](#maintainers)
- [License](#license)

## Finding opportunities to contribute

There are two common ways to find opportunities to contribute:

- [Project Boards](https://github.com/blockstack/designs/projects)
- [Issue Tracker](https://github.com/blockstack/designs/issues)

The project boards is a great place to start. Look for the version that has the label `current`
and look for a ticket in the `To Do` column. Click on the ticket your interested in
and this will link you to the relative issue in the tracker.

If the ticket your interested in is being worked, feel free to provide feedback.

Otherwise, leave a comment addressing one of the [repo maintainers](#maintainers) to get
the conversation started.

Whether you are a veteran programmer, beginner programmer, or don't program at all, we
are positive you will find a place to helping us build a decentralized internet!

[Just Ask!](http://chat.blockstack.org/)

[^ Back To The Top](#contributing-to-blockstack)

## Filenaming & directory structure

Each project team has a directory, seen below, and in each of the team directories are projects. Each project contains 2 standard directories for quick navigation to find files that are;
* compositions or working files with the following filename structure
  * [filename]-[Year][Month].ext
  * Example: brand-1610.sketch
* assets files
* support and reference files

```
design/
├── example-project1/
│   ├── filename-[Year][Month].sketch
│   ├── assets/
│   └── support-files/
└── example-project2/
    ├── filename-[Year][Month].sketch
    ├── assets/
    └── support-files/

```

[^ Back To The Top](#contributing-to-blockstack)

## Install & Setup Git LFS:

[›› More info on Git LFS](https://git-lfs.github.com/)

NOTE: Each new project [example-project1] requires tracking setup. See examples at the bottom of the tracking list below

* Files and folders to be tracked

```
*.sketch (.gitattributes)
*.psd (.gitattributes)
*.psb (.gitattributes)
*.ai (.gitattributes)
*.zip (.gitattributes)
*.indd (.gitattributes)
*.pdf (.gitattributes)
*.ppt (.gitattributes)
*.mov (.gitattributes)
*.eps (.gitattributes)
*.tif (.gitattributes)
*.mp4 (.gitattributes)
*.mp3 (.gitattributes)
*.mv4 (.gitattributes)
*.avi (.gitattributes)
*.m4v (.gitattributes)
*.aaf (.gitattributes)
*.aep (.gitattributes)
*.aet (.gitattributes)
*.indl (.gitattributes)
*.indt (.gitattributes)
*.indb (.gitattributes)
*.dmg (.gitattributes)
*.xcodeproj (.gitattributes)
*.png (.gitattributes)
*.gif (.gitattributes)
*.jpeg (.gitattributes)
*.jpg (.gitattributes)
*.svg (.gitattributes)
*.tar.gz (.gitattributes)
*.qxd (.gitattributes)
*.asc (.gitattributes)
*.csv (.gitattributes)
*.doc (.gitattributes)
*.dot (.gitattributes)
*.gdoc (.gitattributes)
*.pages (.gitattributes)
*.myo (.gitattributes)
*.myob (.gitattributes)
*.tax (.gitattributes)
*.ofx (.gitattributes)
*.qif (.gitattributes)
*.otf (.gitattributes)
*.ttf (.gitattributes)
*.woff (.gitattributes)
*.ase (.gitattributes)
*.bmp (.gitattributes)
*.icns (.gitattributes)
*.ico (.gitattributes)
*.pict (.gitattributes)
*.pdd (.gitattributes)
*.tga (.gitattributes)
*.tiff (.gitattributes)
*.cdr (.gitattributes)
*.ps (.gitattributes)
*.gslides (.gitattributes)
*.key (.gitattributes)
*.keynote (.gitattributes)
*.pez (.gitattributes)
*.pot (.gitattributes)
*.pptx (.gitattributes)
*.thmx (.gitattributes)
*.aiff (.gitattributes)
*.wav (.gitattributes)
*.m4a (.gitattributes)
*.wma (.gitattributes)
*.mp2 (.gitattributes)
*.gsm (.gitattributes)
*.aac (.gitattributes)
*.swa (.gitattributes)
*.vox (.gitattributes)
*.psf (.gitattributes)
*.band (.gitattributes)
*.logic (.gitattributes)
*.gsheet (.gitattributes)
*.xlk (.gitattributes)
*.xls (.gitattributes)
*.xlsb (.gitattributes)
*.xlsm (.gitattributes)
*.xlsx (.gitattributes)
*.xlt (.gitattributes)
*.xltm (.gitattributes)
*.xlw (.gitattributes)
*.tsv (.gitattributes)
*.asf (.gitattributes)
*.dat (.gitattributes)
*.flv (.gitattributes)
*.fla (.gitattributes)
*.mpeg (.gitattributes)
*.mpg (.gitattributes)
*.rm (.gitattributes)
*.fcp (.gitattributes)
*.ppj (.gitattributes)
*.prproj (.gitattributes)
*.imovieproj (.gitattributes)
*.bin (.gitattributes)
*.diff (.gitattributes)
*.gzip (.gitattributes)
*.rar (.gitattributes)
*.tar (.gitattributes)
*.img (.gitattributes)
*.iso (.gitattributes)
example-project1/* (.gitattributes)
example-project2/* (.gitattributes)
```

[^ Back To The Top](#contributing-to-blockstack)

## Using the issue tracker

The [issue tracker](https://github.com/blockstack/designs/issues) is the preferred channel for [bug reports](#bug-reports), [features requests](#feature-requests) and [submitting pull requests](#pull-requests), but please respect the following
restrictions:

* Please **do not** use the issue tracker for personal support requests.  Please use the [Forum](https://forum.blockstack.org) or [Slack](http://chat.blockstack.org) as they are better places to get help.

* Please **do not** derail or troll issues. Keep the discussion on topic and respect the opinions of others.

* Please **do not** post comments consisting solely of "+1" or ":thumbsup:". Use [GitHub's "reactions" feature](https://github.com/blog/2119-add-reactions-to-pull-requests-issues-and-comments) instead. We reserve the right to delete comments which violate this rule.

### When reporting a bug, include:

* Operating system and version (Windows, Mac OS X, Android, iOS, Win10 Mobile)

* Browser and version (Chrome, Firefox, Safari, IE, MS Edge, Opera 15+, Android Browser)

* Reduced test cases and potential fixes using [JS Bin](https://jsbin.com)

### Issues and labels

Our bug tracker utilizes several labels to help organize and identify issues. Here's what they represent and how we use them:

- `backlog` - Issues that have yet to be prioritized
- `bug` - Issues where code is demonstrably a problem
- `copywriting` - Issues that require the art of using words to promote the blockstack brand
- `design` - Issues related to design
- `documentation` - Issue that is specifically for addition, creation or editing of documentation
- `duplicate` - Issues that have already been opened once already
- `enhancement` - Issues that enhance the product
- `feature-request` - Issue whenever a new feature is suggested
- `help wanted` - Issues that require assistance
- `ui` - Issues related to the user interface
- `question` - Issues for general questions about blockstack
- `versions (vX.X.X)` - Issues that are a part of a specific release
- `wont-fix` - Issues that wont-fix

For a complete look at our labels, see the [project labels page](https://github.com/blockstack/designs/labels).

[^ Back To The Top](#contributing-to-blockstack)

## Bug reports

A bug is a _demonstrable problem_ that is caused by the code in the repository. Good bug reports are extremely helpful, so thanks!

Guidelines for bug reports:

0. **Validate and lint your code** &mdash; [validate your HTML](https://html5.validator.nu) and [lint your HTML](https://github.com/twbs/bootlint) to ensure your problem isn't caused by a simple error in your own code.

1. **Use the GitHub issue search** &mdash; [Search for duplicate or closed issues](https://github.com/blockstack/blockstack.org/issues?utf8=%E2%9C%93&q=is%3Aissue).

2. **Check if the issue has been fixed** &mdash; try to reproduce it using the latest `master`, `design` or development branch in the repository.

3. **Isolate the problem** &mdash; ideally create a [reduced test case](https://css-tricks.com/reduced-test-cases/) and a live example. [This JS Bin](https://jsbin.com/lolome/edit?html,output) is a helpful template.


A good bug report shouldn't leave others needing to chase you up for more information. Please try to be as detailed as possible in your report. What is your environment? What steps will reproduce the issue? What browser(s) and OS experience the problem? Do other browsers show the bug differently? What would you expect to be the outcome? All these details will help people to fix any potential bugs.

Example:

> Short and descriptive example bug report title
>
> A summary of the issue and the browser/OS environment in which it occurs. If
> suitable, include the steps required to reproduce the bug.
>
> 1. This is the first step
> 2. This is the second step
> 3. Further steps, etc.
>
> `<url>` - a link to the reduced test case
>
> Any other information you want to share that is relevant to the issue being
> reported. This might include the lines of code that you have identified as
> causing the bug, and potential solutions (and your opinions on their
> merits).

[^ Back To The Top](#contributing-to-blockstack)

## Feature requests

Feature requests are welcome. But take a moment to find out whether your idea fits with the scope and aims of the project. It's up to *you* to make a strong case to convince the project's developers of the merits of this feature. Please provide as much detail and context as possible, providing relevant links, prior art, or live demos whenever possible.

[^ Back To The Top](#contributing-to-blockstack)

## Pull requests

**Working on your first Pull Request?** You can learn how from this *free* series [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)

Good pull requests—patches, improvements, new features—are a fantastic help. They should remain focused in scope and avoid containing unrelated commits.

**Please ask first** before embarking on any significant pull request (e.g. implementing features, refactoring code, porting to a different language), otherwise you risk spending a lot of time working on something that the project's developers might not want to merge into the project.

Please adhere to the [Blockstack Brand Guide](https://github.com/blockstack/designs/issues/247), [coding guidelines](#code-guidelines) used throughout the project (indentation, accurate comments, etc.), and any other requirements (such as test coverage).

Ensure that your pull requests are small components. This assists both with your pull request getting accepted and makes it much easier/faster for the repository maintainer to merge in your pull request.

When contributing to Blockstack's documentation, you should edit the documentation source files in [the `/app/` directory of the `master` branch](https://github.com/blockstack/designs/tree/master/app).

Adhering to the following process is the best way to get your work included in the project:

1. [Fork](https://help.github.com/fork-a-repo/) the project, clone your fork,
   and configure the remotes:

   ```bash
   # Clone your fork of the repo into the current directory
   git clone https://github.com/<your-username>/designs.git
   # Navigate to the newly cloned directory
   cd designs
   # Assign the original repo to a remote called "upstream"
   git remote add upstream https://github.com/blockstack/designs.git
   ```

2. If you cloned a while ago, get the latest changes from the `contribute` branch upstream:

   ```bash
   git checkout -b contribute
   git pull upstream contribute
   ```

3. Create a new topic branch (off the main project development branch) to
   contain your feature, change, or fix, followed by semantic versioning
   using your Github username and 'patch':

   ```bash
   git checkout -b <topic-branch-name>-<github-username>-patch
   ```

4. Commit your changes in logical chunks. Please adhere to these [git commit
   message guidelines](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
   or your code is unlikely be merged into the main project. Use Git's
   [interactive rebase](https://help.github.com/articles/interactive-rebase)
   feature to tidy up your commits before making them public.

5. Locally merge (or rebase) the upstream development branch into your topic branch:

   ```bash
   git pull [--rebase] upstream master
   ```

6. Push your topic branch up to your fork:

   ```bash
   git push origin <topic-branch-name>
   ```

7. [Open a Pull Request](https://help.github.com/articles/using-pull-requests/) against the `design` branch.a
    - Add a clear title and description
    - Include screenshots of the before and after if your changes include differences in HTML/CSS. Drag and drop the images into the body of your pull request.
    - Reference any relevant issues or supporting documentation in your PR (ex. “Closes #37.”)
    - Make sure submitted code has no conflicts

**IMPORTANT**: By submitting a patch, you agree to allow the project owners to
license your work under the terms of the [MPL-2.0 License](https://github.com/blockstack/blockstack-browser/blob/master/LICENSE.md) (if it
includes code changes) and under the terms of the
[Creative Commons Attribution 3.0 Unported License](docs/LICENSE.md)
(if it includes documentation changes).

[^ Back To The Top](#contributing-to-blockstack)

## Code guidelines

### HTML

[Adhere to the Code Guide.](http://codeguide.co/#html)

- Use tags and elements appropriate for an HTML5 doctype (e.g., self-closing tags).

### JS

- No semicolons (in client-side JS)
- 2 spaces (no tabs)
- strict mode
- "Attractive"
- Don't use jQuery (no "$" allowed)

### Checking code

Run `npm run dev` before committing to ensure your changes follow our coding standards.

[^ Back To The Top](#contributing-to-blockstack)

## Maintainers

<table>
  <tbody>
    <tr>
      <td align="center" valign="top">
        <img width="150" height="150" src="https://github.com/guylepage3.png?s=150">
        <br>
        <a href="https://github.com/guylepage3">Guy Lepage</a>
        <br>
        <p>master branch</p>
      </td>
     </tr>
  </tbody>
</table>

[^ Back To The Top](#contributing-to-blockstack)

## License

By contributing your code, you agree to license your contribution under the [MPL-2.0 License](https://github.com/blockstack/blockstack-browser/blob/master/LICENSE.md).
