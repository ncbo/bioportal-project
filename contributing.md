# Contributing to OntoPortal (and BioPortal)

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to BioPortal/OntoPortal sotware, which is hosted in the [NCBO project](https://github.com/ncbo) on GitHub. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

#### Table Of Contents

[Code of Conduct](#code-of-conduct)

[I don't want to read this whole thing, I just have a question!!!](#i-dont-want-to-read-this-whole-thing-i-just-have-a-question)

[What should I know before I get started?](#what-should-i-know-before-i-get-started)
  * [Don't try to install from GitHub source](#don't-try-to-install-from-GitHub-source)
  * [BioPortal/OntoPortal repositories](#bioportal/ontoportal-repositories)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Your First Code Contribution](#your-first-code-contribution)
  * [Pull Requests](#pull-requests)

## Code of Conduct

This project and everyone participating in it is governed by the [Terms of Service](https://bioportal.bioontology.org/terms). By participating, you are expected to uphold this code. 

## I don't want to read this whole thing I just have a question!!!

> **Note:** Please don't file an issue to ask a question. You'll get faster results by using the resources below.

We have an official message board where the community chimes in with helpful advice if you have questions.

* [BioPortal/OntoPortal/Virtual Appliance message board](https://mailman.stanford.edu/mailman/listinfo/bioontology-support) Or you can just send email to [the moderated list](support@bioontology.org).

## What should I know before I get started?

### Don't try to install from GitHub source

We encourage anyone wanting to start developing with BioPortal/OntoPortal software to get a copy of the [Virtual Appliance](https://www.bioontology.org/wiki/Category:NCBO_Virtual_Appliance), then submit changes to our repositories based on changes to that code base. Read the Repositories section below for better understanding of our rationale, but basically, we have a lot of installation steps that are a bit one-off.

### BioPortal/OntoPortal repositories

The GitHub ncbo project contains mahy repositories that are not critical to BioPortal operations. Conversely, there are one or two critical repositories that you do not have access to.

You do have to install several different code bases (repositories) as well as some back-end services. Please contact us for more information via the support list.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, you can check our [issue board](https://app.zenhub.com/workspaces/bioportal-5cd9eda6c115951dc85934af) as you might find out that you don't need to create one. When you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report). You can submit it via the support list, or via a ticket in the appropriate ncbo repository, or via the bioportal-project repository.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### Before Submitting A Bug Report

* **Perform a [cursory search of the [issue repository](https://app.zenhub.com/workspaces/bioportal-5cd9eda6c115951dc85934af) and/or the [support archive](http://ncbo-support.2288202.n4.nabble.com/) to see if the problem has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). If you've determined which repository your bug is related to, create an issue on that repository and provide the following information (sorry, we don't have a template yet):

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* ** If you can describe exactly what time the issue occurred, we can more confidently review our (rather large) logs to look for reports related to your issue. 
* **Describe the exact steps which reproduce the problem** in as many details as possible. For example, what you were trying to do and what you expected. 
* **Provide specific examples to demonstrate the steps**. Include links to your ontology, the BioPortal page(s) you were visiting, and/or copy/pasteable snippets of your results.  If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**

Include details about your configuration and environment:

* **What's the name and version of the browser you're using**?
* **Are you running BioPortal in a virtual machine?** If so, which VM software are you using and which operating systems and versions are used for the host and the guest?

You don't have to worry about the labels that are available, but you may use them if you want. We will review the issue and adjust labels as appropriate.

### Requesting Features/Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for BioPortal/OntoPortal, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion :pencil: and find related suggestions :mag_right:.

We recommend you review the existing tickets/emails (as suggested for Bug Reports above) before submitting a detailed request or suggestion.

For simple requests/suggestions, an email to our support list is the simplest route. We will attempt to respond to your email and document your suggestion. 

If you want to document a request in more detail, you may use our ticket system as described above for reporting bugs.

#### How Do I Submit A (Good) Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/). If you've determined which repository your enhancement suggestion is related to, create an issue on that repository and provide the following information:

* **Use a clear and descriptive title** for the issue to identify the suggestion.
* **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
* **Provide specific examples to demonstrate the steps**. Include copy/pasteable snippets which you use in those examples, as [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
* **Include screenshots and animated GIFs** which help you demonstrate the steps or point out the part of BioPortal which the suggestion is related to. 
* **Explain why this enhancement would be useful** to most BioPortal/OntoPortal users and isn't something that can or should be implemented as an external application.
* **List some other applications where this enhancement exists.**
* **Specify which version of BioPortal/OntoPortal you're using.** 

#### Local development

BioPortal/OntoPortal can be developed locally; unfortunately, we do not have instructions on how to do this yet.

### Pull Requests

The process described here has several goals:

- Maintain our software's quality
- Fix problems that are important to users
- Engage the community in working toward the best possible OntoPortal
- Enable a sustainable system for OntoPortal's maintainers to review contributions

Please follow these steps to have your contribution considered by the maintainers:

1. Test your code before submitting a pull request with it.
2. [Optional] Contact us to discuss your pull request, to be sure we will be able to use it. 
3. Follow the existing style in the software you are modifying. Except: Please provide more documentation than the existing stye does.
4. After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) are passing <details><summary>What if the status checks are failing?</summary>If a status check is failing, and you believe that the failure is unrelated to your change, please leave a comment on the pull request explaining why you believe the failure is unrelated. A maintainer will re-run the status check for you. If we conclude that the failure was a false positive, then we will open an issue to track that problem with our status check suite.</details>

While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.

