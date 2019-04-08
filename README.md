<!--
name: README.md
description: This file contains important information for the repository.
author: while-true-do.io
contact: hello@while-true-do.io
license: BSD-3-Clause
-->
<!-- github shields -->
![](https://img.shields.io/github/license/while-true-do/doc-library.svg?style=flat)
![](https://img.shields.io/github/issues/while-true-do/doc-library.svg?style=flat)
![](https://img.shields.io/github/issues-pr/while-true-do/doc-library.svg?style=flat)
<!-- travis testing shields -->
[![Build Status](https://travis-ci.org/while-true-do/doc-library.svg?branch=master)](https://travis-ci.org/while-true-do/doc-library)

# doc-library

A repository containing some documents and templates.

## Motivation

During the past years, while-true-do.io opened and closed some repositories. We
faced the situation, that maintaining Guidelines and other general purpose
documents was somewhat tedious. Keeping track of documents and templates should
be easy and centrally manageable.

## Description

This repository keeps track of common documents and templates.

### Documents

Documents should not be included in your repository but linked. They will only
see updates in the doc-library.

-   [Code of Conduct](./docs/CODE_OF_CONDUCT.md)
-   [Style Guide](./docs/STYLE_GUIDE.md)
-   [Contribution Guideline](./docs/CONTRIBUTING.md)
-   [Versioning](./docs/VERSIONING.md)

### Templates

Templates are meant as a Starting Point. You should adjust them to your needs
and liking.

-   [.editorconfig](./templates/.editorconfig.j2)
-   [.gitattributes](./templates/.gitattributes.j2)
-   [.gitignore](./templates/.gitignore.j2)
-   [.gitmessage](./templates/.gitmessage.j2)
-   [LICENSE](./templates/LICENSE.j2)
-   [kudos.txt](./templates/kudos.txt.j2)
-   [README.md](./templates/README.md.j2)

## Requirements

None.

## Installation

Install from [Github](https://github.com/while-true-do/doc-library)

```
git clone https://github.com/while-true-do/doc-library.git
```

## Usage

1.  Enable .gitmessage as commit template

    ```
    # Only for the repository
    git config commit.template .gitmessage
    # Global for all repositories
    git config --global commit.template .gitmessage
    ```

2.  Copy and rename the files from ./templates to the desired destination
3.  Edit the files properly (at least "{{ WTD_REPO_NAME }}" must be replaced)
4.  Update all "TODO" Sections to your likings

## Testing

Most of the "generic" tests are located in the
[Test Library](https://github.com/while-true-do/test-library). Tests and
instructions for a single repository are located in the
[Test Directory](./tests).

## Contribute

Thank you so much for considering to contribute. We are very happy, when somebody
is joining the hard work. Please fell free to open
[Bugs, Feature Requests](https://github.com/while-true-do/doc-library/issues) or
[Pull Requests](https://github.com/while-true-do/doc-library/pulls) after
reading the [Contribution Guideline](https://github.com/while-true-do/doc-library/blob/master/docs/CONTRIBUTING.md).

See who has contributed already in the [kudos.txt](./kudos.txt).

## License

This work is licensed under a [BSD-3-Clause License](https://opensource.org/licenses/BSD-3-Clause).

## Contact

-   Site <https://while-true-do.io>
-   Twitter <https://twitter.com/wtd_news>
-   Code <https://github.com/while-true-do>
-   Mail [hello@while-true-do.io](mailto:hello@while-true-do.io)
-   IRC [freenode, #while-true-do](https://webchat.freenode.net/?channels=while-true-do)
-   Telegram <https://t.me/while_true_do>


<!-- ./Footer (auto generated) -->
