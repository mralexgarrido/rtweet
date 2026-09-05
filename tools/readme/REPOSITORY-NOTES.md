# Notes for this repository copy

## Scope

This is the `mralexgarrido/rtweet` repository, with default branch `premium-search-patch`. The inherited package metadata declares version 0.7.0. Its existing upstream authors, dependency declarations, license notices, and bug-report metadata are preserved.

Do not present upstream build badges, download totals, review badges, or a historical API quota as evidence that this local copy has passed a current compatibility check. Determine whether a reported issue belongs to a local change or reproduces upstream before choosing a reporting destination.

## Preserve upstream history

The original [README.md](https://github.com/mralexgarrido/rtweet/blob/cb8f5533f6be0510d8a1b5440e82cbc174d694ca/README.md) and [README.Rmd](https://github.com/mralexgarrido/rtweet/blob/cb8f5533f6be0510d8a1b5440e82cbc174d694ca/README.Rmd) remain available at the pre-documentation baseline. The presentation update does not delete package functions, figures, vignettes, citations in that historical documentation, or Git history.

## Update the introduction

Edit the root README.Rmd source and keep README.md consistent with its text. The source retains the `github_document` output type. In a suitable R environment, render the source with `rmarkdown::render("README.Rmd")` from the repository root, then inspect the Markdown diff and links.

The new introduction contains no executable API examples. A documentation render should not require account credentials or contact Twitter/X. Rendering and package tests were not executed as part of this presentation-only update; inspect actual results before calling either verified.

Do not regenerate old network-dependent examples merely to update the repository introduction. Confirm that examples will not publish content or alter an account before running them.

## Package changes and releases

For application-code work, record the R and dependency versions, exact commit, test scope, network access requirements, and endpoint compatibility checked. Never include credentials or private data in logs, fixtures, issues, or commits. A package build is not proof of current service access.

Make focused changes on a branch. Obtain maintainer approval before merging, tagging, publishing a package/release, or modifying account access. Do not alter the package version or mark it actively supported solely to improve its appearance.

Suggested About description: **Repository copy of the rtweet R package, preserving upstream source and local patch history.** Suggested topics: `r`, `rtweet`, `twitter-api`, `data-collection`. Do not add a live-app URL to a package repository. These are presentation suggestions, not settings modified by this document.

## Rollback

Before merge, closing the documentation PR leaves the default branch untouched. After an approved merge, revert the documentation commit through a new PR. The baseline is `cb8f5533f6be0510d8a1b5440e82cbc174d694ca`; do not force-push or rewrite upstream history.
