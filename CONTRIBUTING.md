# Contributing

Please feel free to contribute to the quality of this content by submitting PR's for improvements to code snippets, explanations, etc. If there's any doubt or if you think that a word/phrase is used confusingly, **before submitting a PR, open an issue to ask about it.**

However, if you choose to contribute content (not just typo corrections) to this repo, you agree that you're giving me a non-exclusive license to use that content for the book, as I (and my publisher) deem appropriate. You probably guessed that already, but I just have to make sure the lawyers are happy by explicitly stating it.

## Reading Experience (Chapter/Section links, etc)

I understand that reading one long .md file, with no relative cross links to other sections/etc, is not the preferred reading experience for most of you. As such, it's totally reasonable to want to file an issue/PR to add those kinds of features.

This topic has been brought up many times, and I've considered it. For now, I **do not** accept these kinds of changes into the repo.

The main purpose of my book repos is to track and manage the content for the purposes of publication (paid-for ebooks and print books). I do this in the open because I also care about providing free and early access to the content, to make sure there is no paywall barrier to learning.

As such, this repo **is not optimized for your reading experience.**

The primary reading experience, likely the most pleasant one for many of you, is the ebooks or print books, which [are available for sale](http://ssearch.oreilly.com/?q=%22you+don%27t+know+js%22&x=0&y=0). The balance I'm striking here is releasing the content for free, but selling the reading experience. Other authors make different decisions on that balance, but that's what I've come to for now.

I hope you continue to enjoy and benefit from the content, and I also hope you value it enough to [purchase the best reading experience](http://ssearch.oreilly.com/?q=%22you+don%27t+know+js%22&x=0&y=0) in the ebook/print form.

## Editions

The current state of this repo is the 1st Edition of the published form of these books. That means that you should have almost exactly the same content here as in the ebooks or printed books, with only minor variances in typos, formatting, etc.

I generally am not accepting any changes to the current repo, as I do not want this content to diverge from what's in the published books. There are over a hundred filed issues/PRs for changes that are being collected for the 2nd Edition, but work has not yet begun on that.

So, if you find something that should be fixed, just know that it will likely sit for awhile in that batch until it's time to make the 2nd Edition updates. At that time, my plan is to make separate branches to track the editions.

## Typos?

These books go through official editing with the publisher, and typos are likely all caught at that stage. As such, **typos are not a big concern for this repo**.

If you're going to submit a PR for typo fixes, please be measured in doing so by collecting several small changes into a single PR (in separate commits). Or, **just don't even worry about them for now,** because we'll get to them later. I promise.

## Search First!

Also, if you have any questions or concerns, please make sure to search the issues (both open and closed!) first, to keep the churn of issues to a minimum. I want to keep my focus on writing these books as much as possible.

## Contribution workflow and AI assistance

This section applies only to [ogarciarevett/You-Dont-Know-JS](https://github.com/ogarciarevett/You-Dont-Know-JS), an owner-controlled fork of [getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS). It does not change upstream policy or authorize an upstream PR. For this fork, it supersedes conflicting inherited wording only about the PR workflow, AI disclosure, and AI attribution trailers; substantive quality, review, CLA/DCO, license, security, and testing requirements remain in force.

All contributors and agents must work on a topic branch and submit changes by pull request to `master`. Only the human repository owner, after confirming exact GitHub account control, may choose direct changes to `main` or the default branch; existing protections still apply. Agents must never directly update those branches, even when authenticated with the owner's account. GitHub account authentication does not establish that a human is operating it.

AI assistance is welcome. In the PR description, disclose each tool, the model identifier when exposed, and the scope of its help. If the model is not exposed, say `unknown (not exposed)`; do not guess. This scoped disclosure is required even if an inherited instruction otherwise discourages tool attribution.

Example disclosure (replace the example with accurate details):

```text
AI assistance: tool = coding assistant; model = unknown (not exposed).
Scope: helped draft the change and tests.
Human responsibility: I reviewed and understand every submitted change.
Validation: list actual checks and results, or explain checks not run.
```

A named human must review and understand the complete change, verify its tests and claims, check security and privacy, and confirm the right to contribute all code and dependencies under the applicable licenses. AI assistance does not waive existing review, CLA/DCO, signing, coverage, or CI requirements. Follow the existing commit conventions, including Conventional Commits where required. No AI `Co-authored-by` trailer or one-line commit attribution is required; any required human credit or DCO sign-off still applies.

Do not include secrets, personal data, private prompts, conversation transcripts, or hidden reasoning in the disclosure. None is required. Provide only the tool/model, scope, human accountability, and actual validation evidence.
