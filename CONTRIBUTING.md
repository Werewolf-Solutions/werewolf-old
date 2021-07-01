# Contributing to Werewolf

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to Werewolf and its softwares, libraries and front-end, which are hosted in [Werewolf Organization](https://github.com/Werewolf-Solutions) on GitHub. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

#### Table Of Contents

[Code of Conduct](#code-of-conduct)

[What should I know before I get started?](#what-should-i-know-before-i-get-started)
  * [Werewolf structure](#werewolf-structure)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Your First Code Contribution](#your-first-code-contribution)
  * [Pull Requests](#pull-requests)

## Code of Conduct

This project and everyone participating in it is governed by the [Werwolf Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to ```[werewolf@github.com](mailto:werewolf@github.com).```

> **Note:** [Please don't file an issue to ask a question.](https://werewolf.solutions) You'll get faster results by using the resources below.

## What should I know before I get started?

### Werewolf structure

- softwares / libraries
  - [accounting](https://github.com/Werewolf-Solutions/accounting): this is a software written in JS that gets a budget and does the accounting.
  - [trading-bot](https://github.com/Werewolf-Solutions/trading-bot): this is the trading-bot software that allows to connect to multiple exchanges and trade in an automatic way with your own strategies.
  - [helpers](https://github.com/Werewolf-Solutions/helpers): this is the library to handle math, dates, arrays and all other stuff we need
  - [blockchain](https://github.com/Werewolf-Solutions/blockchain): this is the library that connects to the various blockchains (Bitcoin, Ethereum, BSC, Polygon, . . .)
  -  . . .

- [desktop (React app)](https://github.com/Werewolf-Solutions/desktop)
  - [Components](https://github.com/Werewolf-Solutions/desktop/src/Components)
      - [Layout](https://github.com/Werewolf-Solutions/desktop/src/Components/Layout): this contains the main Layout of the app, with header, body, footer

      ![werewolf-test](werewolf-test.png)

      - [Investments](https://github.com/Werewolf-Solutions/desktop/src/Components/Investments): this contains everything about investments, with cefi (centrilized finance), defi (decentrilized finance) and trading-bots (on DEXes and CEXes)

      ![werewolf-test](werewolf-test.png)

      - [Accounting](https://github.com/Werewolf-Solutions/desktop/src/Components/Accounting): this contains everything about accounting, costs, incomes etc

      ![werewolf-test](werewolf-test.png)

      - [Settings](https://github.com/Werewolf-Solutions/desktop/src/Components/Settings): this contains everything about settings, edit profile, 2FA etc

      ![werewolf-test](werewolf-test.png)


## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report for Werewolf. Following these guidelines helps maintainers and the community understand your report :pencil:, reproduce the behavior :computer: :computer:, and find related reports :mag_right:.

Before creating bug reports, please check [this list](#before-submitting-a-bug-report) as you might find out that you don't need to create one. When you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report). Fill out [the required template](https://github.com/Werewolf-Solutions/werewolf/.github/BUG_REPORT.md), the information it asks for helps us resolve issues faster.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### Before Submitting A Bug Report

* **Check the [FAQs on the forum](https://werewolf.solutions)** for a list of common questions and problems.
* **Determine [which repository the problem should be reported in](#werewolf-structure)**.
* **Perform a [cursory search](https://github.com/search?q=+is%3Aissue+user%3AWerewolf-Solutions)** to see if the problem has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined [which repository](#werewolf-structure) your bug is related to, create an issue on that repository and provide the following information by filling in [the template](https://github.com/Werewolf-Solutions/werewolf/.github/BUG_REPORT.md).

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible. For example, start by explaining how you started, e.g. which command exactly you used in the terminal. When listing steps, **don't just say what you did, but explain how you did it**. For example, .
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem.
* **If you're reporting that Werewolf crashed**
* **If the problem is related to performance or memory**
* **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Provide more context by answering these questions:

* **Did the problem start happening recently** (e.g. after updating to a new version of Werewolf) or was this always a problem?
* If the problem started happening recently, **can you reproduce the problem in an older version of Werewolf?** What's the most recent version in which the problem doesn't happen? You can download older versions of Werewolf from [the releases page](https://github.com/Werewolf-Solutions/werewolf/releases).
* **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.
* If the problem is related to working with files (e.g. opening and editing files), **does the problem happen for all files and projects or only some?** Does the problem happen only when working with local or remote files (e.g. on network drives), with files of a specific type (e.g. only JavaScript or Python files), with large files or files with very long lines, or with files in a specific encoding? Is there anything else special about the files you are using?

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for Werewolf, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion :pencil: and find related suggestions :mag_right:.

Before creating enhancement suggestions, please check [this list](#before-submitting-an-enhancement-suggestion) as you might find out that you don't need to create one. When you are creating an enhancement suggestion, please [include as many details as possible](#how-do-i-submit-a-good-enhancement-suggestion). Fill in [the template](https://github.com/Werewolf-Solutions/werewolf/.github/FEATURE_REQUEST.md), including the steps that you imagine you would take if the feature you're requesting existed.

#### Before Submitting An Enhancement Suggestion

* **Determine [which repository the enhancement should be suggested in](#werewolf-structure).**
* **Perform a [cursory search](https://github.com/search?q=+is%3Aissue+user%3AWerewolf-Solutions)** to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined [which repository](#werewolf-structure) your enhancement suggestion is related to, create an issue on that repository and provide the following information:

* **Use a clear and descriptive title** for the issue to identify the suggestion.
* **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
* **Provide specific examples to demonstrate the steps**. Include copy/pasteable snippets which you use in those examples, as [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
* **Include screenshots and animated GIFs** which help you demonstrate the steps or point out the part of Atom which the suggestion is related to. You can use [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux.
* **Explain why this enhancement would be useful** to most Werewolf users
* **Specify the name and version of the OS you're using.**

### Your First Code Contribution

Unsure where to begin contributing to Werewolf? You can start by looking through these `beginner` and `help-wanted` issues:

* [Beginner issues][beginner] - issues which should only require a few lines of code, and a test or two.
* [Help wanted issues][help-wanted] - issues which should be a bit more involved than `beginner` issues.

Both issue lists are sorted by total number of comments. While not perfect, number of comments is a reasonable proxy for impact a given change will have.

#### Local development

Werewolf Core and all softwares can be developed locally.

* connect your own server

### Pull Requests

The process described here has several goals:

- Maintain Werewolf's quality
- Fix problems that are important to users
- Engage the community in working toward the best possible Werewolf
- Enable a sustainable system for Werewolf's maintainers to review contributions

Please follow these steps to have your contribution considered by the maintainers:

1. Follow all instructions in [the template](https://github.com/Werewolf-Solutions/werewolf/tree/main/.github/PULL_REQUEST_TEMPLATE.md)
2. Follow the [styleguides](#styleguides)
3. After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) are passing <details><summary>What if the status checks are failing?</summary>If a status check is failing, and you believe that the failure is unrelated to your change, please leave a comment on the pull request explaining why you believe the failure is unrelated. A maintainer will re-run the status check for you. If we conclude that the failure was a false positive, then we will open an issue to track that problem with our status check suite.</details>

While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.