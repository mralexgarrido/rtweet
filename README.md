<!-- README.md is maintained from README.Rmd. Update both when changing this introduction. -->

# rtweet: repository copy

An inherited R package for collecting and organizing Twitter data, retained in Alex Garrido's GitHub account with its upstream source and history.

**This repository is not the upstream rtweet project, and its current Twitter/X API compatibility has not been verified.** The package metadata here declares version 0.7.0. The local default branch is `premium-search-patch`; a recent documentation edit should not be interpreted as a new package release or a tested API update.

[Upstream project](https://github.com/ropensci/rtweet) · [Package metadata](DESCRIPTION) · [Repository notes](tools/readme/REPOSITORY-NOTES.md) · [Historical README](https://github.com/mralexgarrido/rtweet/blob/cb8f5533f6be0510d8a1b5440e82cbc174d694ca/README.md)

## What this copy contains

The inherited package implements functions for working with Twitter REST and streaming APIs and organizing returned data in R. This repository preserves that implementation and the local change history. It is an R package, not a hosted web application or an independent replacement for the upstream project.

The pre-documentation baseline is commit `cb8f5533f6be0510d8a1b5440e82cbc174d694ca`, dated December 10, 2020. Review the actual source and commit differences before relying on a local patch.

## Before using the package

Inspect [DESCRIPTION](DESCRIPTION) for the dependencies and package metadata, and choose a reviewed commit for reproducible work. Inherited CRAN and `ropensci/rtweet` installation instructions target those distributions, not automatically this repository's local branch.

The [historical README](https://github.com/mralexgarrido/rtweet/blob/cb8f5533f6be0510d8a1b5440e82cbc174d694ca/README.md) contains the original examples, figures, citations, and upstream badges. Its authentication instructions, rate limits, package comparisons, and service assumptions describe the inherited documentation; they are not current guarantees. Confirm API access, permitted uses, endpoint availability, and applicable limits with the service provider before running network-dependent examples.

Do not commit tokens, account credentials, private messages, or sensitive datasets. Test with controlled data and avoid running examples that publish, follow accounts, or otherwise modify an account unless those actions are intended and authorized.

## Documentation and maintenance

The original introduction is preserved through its immutable history link rather than discarded or rewritten in Git history. Upstream package code, metadata, license files, references, and figures are unchanged by this presentation update.

Use [repository notes](tools/readme/REPOSITORY-NOTES.md) for the local documentation workflow and validation boundaries. No maintained-service commitment, new package version, or successful API test is implied by this README.

## Attribution and license

The inherited [DESCRIPTION](DESCRIPTION) credits **Michael W. Kearney** as author and creator, with **Andrew Heiss** and **Francois Briatte** as reviewers. The source comes from the [upstream rtweet project](https://github.com/ropensci/rtweet); original authorship and review credit belong to those contributors.

Package metadata declares **MIT + file LICENSE**. See [LICENSE](LICENSE) and the existing source notices. This repository introduction does not change licensing or claim ownership of upstream work. Alex Garrido is the owner of this GitHub repository copy, not the original author of the package.
