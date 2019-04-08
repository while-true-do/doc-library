<!--
name: CONTRIBUTING.md
description: This file contains the Contribution Code for while-true-do.io.
author: while-true-do.io
contact: hello@while-true-do.io
license: BSD-3-Clause
-->
# Contribution Code

while-true-do.io Contribution Guideline

## Welcome

First off, thanks for taking time to contribute. We really appreciate every
contribution in form of Reports, Requests, Discussions or every other bit,
that will help to grow the project.

Please read the below text carefully before contributing.

## Contents

-   [Code of Conduct](#code-of-conduct)
-   [Project Contribution](#project-contribution)
    -   [Bug Reports](#bug-reports)
    -   [Feature Requests](#feature-requests)
    -   [Code Contribution](#code-contribution)
    -   [Community Work](#community-work)
-   [Additional Guides](#additional-guides)
    -   [Make your Mark](#make-your-mark)
    -   [Versioning Guide](#versioning-guide)
    -   [Style Guide](#style-guide)

## Code of Conduct

In the past, we never faced a situation where a guideline was needed. Everybody
should be aware of good behavior and should know, how to talk to people.

Nevertheless, we are having a document derived from
<https://www.contributor-covenant.org>. Maybe you want to consider reading the
whole [Code of Conduct](./CODE_OF_CONDUCT.md).

## Project Contribution

Contributing to while-true-do.io is appreciated. We are open for new ideas,
helping with the community, bug reports, helps with testing, etc. In this
section you will find some hints. If your way of contribution is not explained
here, please feel free to discuss your idea with us.

### Bug Reports

Reporting Bugs should follow some simple rules:

-   **Check**, if you can find similar Bugs
-   **Describe, what** is happening and what should happen
-   **Explain, why** this is a problem
-   **Add** more details and attachments
-   **Follow up**, if somebody is having questions or needs more details

Formulating your Bug Report as if you are explaining it to a rubber duck
is a very good idea.

### Feature Requests

Requesting a new feature is also following some simple rules:

-   **Check**, if the feature is already requested
-   **Describe, what** your feature will bring to the community
-   **Explain** the criteria to fulfill the request
-   **Add** more details like mock ups, attachments, lists, screenshots
-   **Follow Up** in the discussion to the feature
-   **Be patient**, it may take some time

Small Feature Requests should be written in a User Story.

#### Example

As a user/developer/packager/etc, I need ... , due to ...

-   Criteria 1
-   Criteria 2
-   Criteria 3

### Code Contribution

Contributing Code should be as easy as possible. Therefore, all needed
information should be present in the README.md of each repository. Some basic
rules should be applied.

-   **Open an issue** for each code contribution (see above)
-   **One Contribution** should solve **one issue**
-   **Tested** code is **cool** code
-   **Documented** code is **Maintainable** code
-   **Use file headers and kudos.txt** to [make your mark](#make-your-mark)
-   **Commit Messages** should be useful and self explaining and
    use the .gitmessage as a template, if existing in the repository

#### Example Commit

```
feat: Everything OK Button

A long requested Everything OK Button, which will help us a lot!

- add: everything_ok.py
- remove: not_ok.js
- update: README.md
- update: metadata.json

Resolves: #1234
See also: #4711, #666
```

### Community Work

Contribution does not mean, that one needs to code. You can also help in many
other ways like Blogging, Spreading the word, Testing and Reporting, Drawing,
Writing, participating to events, etc.

Please feel free to reach out to us to discuss your options. We encourage you
to help us in any way you like to.

## Additional Guides

When contributing, you may face situations where you need a little bit more
guidance. In this section, we are collecting documents, which may help you. If
something is missing, please feel free to reach out to us.

### Make your mark

We want to thank everybody, who chooses to help the project and contributing.
We thought about, how one can leave it's mark in the code or repository,
without relying on technologies from hosted repository software. There are 2
ways to "Make your mark."

#### Content

By default we are using the below data to mark our work.

- name: <name of the file>
- description: <This file ...>
- author: while-true-do.io
- license: <proper License>

Everything else is optional or specific for the file and repository.

#### File headers

We are maintaining file headers for all files. This should ensure that everybody
is getting the credits he deserves. The header should also give some guidance,
where a user can reach out to for contact. The content is maintained in the
[kudos.txt](https://github.com/kudos-txt) format.

If a header is missing, please feel free to add one.

**Exceptions:** Some files are already for informational purposes only. These
files are excluded from this policy. As an example, you can think of the
following files:

-   LICENSE
-   package.json
-   meta/main.yml (ansible-galaxy meta file)
-   kudos.txt

**Example:** A typical example for such a header may look like this.

```
# name: .editorconfig
# description: This file helps to configure your editor via editorconfig.
# author: while-true-do.io
# license: BSD-3-Clause
# reference: https://editorconfig.org/
```

#### kudos.txt
<!-- FIXME: kudos.txt is not done, yet. The below paragraph should be reviewed
after kudos.txt 1.0.0 -->
We are maintaining a [kudos.txt](https://github.com/kudos-txt). We want to
ensure everybody is getting the gratitude he deserves. Please feel free to add
yourself to the [kudos.txt](../kudos.txt) file, present in each repository.

If the kudos.txt file is missing, please feel free to add one. You can find a
template in the [doc-library](https://github.com/while-true-do/doc-library).

### Versioning Guide

We are sticking to **Semantic Versioning** for all repositories and products.
You can read everything about it in [VERSIONING.md](./VERSIONING.md) or at
the website <https://semver.org/>

Versioning is exclusively done from [members](github.com/while-true-do). Outside
contributors can suggest a version raise in the Issue and PR.

### Style Guide
<!--
FIXME: After finishing the Style Guide, the below paragraph must be re-written.
-->

We are currently working on a Style Guide, which will show details like logos,
ideals, fonts, colors, etc. It's not finished, but improving.

You will find the current Version of the guide in
[STYLE_GUIDE.md](./STYLE_GUIDE.md).
