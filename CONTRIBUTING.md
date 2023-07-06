# Contributing to opentelemetry-go-build-tools

## Development

You can view and edit the source code by cloning this repository:

```sh
git clone https://github.com/open-telemetry/opentelemetry-go-build-tools.git
```

Run `make test` to run the tests instead of `go test`.

There are some generated files checked into the repo. To make sure
that the generated files are up-to-date, run `make` (or `make
precommit` - the `precommit` target is the default).

The `precommit` target also fixes the formatting of the code and
checks the status of the go module files.

If after running `make precommit` the output of `git status` contains
`nothing to commit, working tree clean` then it means that everything
is up-to-date and properly formatted.

## Pull Requests

### How to Send Pull Requests

Everyone is welcome to contribute code to `opentelemetry-go-build-tools` via
GitHub pull requests (PRs).

Open a pull request against the main `opentelemetry-go-build-tools` repo.
Be sure to add the pull request ID to the entry you added to `CHANGELOG.md`.

### How to Receive Comments

* If the PR is not ready for review, please put `[WIP]` in the title,
  tag it as `work-in-progress`, or mark it as
  [`draft`](https://github.blog/2019-02-14-introducing-draft-pull-requests/).
* Make sure CLA is signed and CI is clear.

### How to Get PRs Merged

A PR is considered to be **ready to merge** when:

* It has received two approvals from Collaborators/Maintainers (at
  different companies). This is not enforced through technical means
  and a PR may be **ready to merge** with a single approval if the change
  and its approach have been discussed and consensus reached.
* Feedback has been addressed.
* Any substantive changes to your PR will require that you clear any prior
  Approval reviews, this includes changes resulting from other feedback. Unless
  the approver explicitly stated that their approval will persist across
  changes it should be assumed that the PR needs their review again. Other
  project members (e.g. approvers, maintainers) can help with this if there are
  any questions or if you forget to clear reviews.
* It has been open for review for at least one working day. This gives
  people reasonable time to review.
* Trivial changes (typo, cosmetic, doc, etc.) do not have to wait for
  one day and may be merged with a single Maintainer's approval.
* `CHANGELOG.md` has been updated to reflect what has been
  added, changed, removed, or fixed.
* `README.md` has been updated if necessary.
* Urgent fix can take exception as long as it has been actively
  communicated.

Any Maintainer can merge the PR once it is **ready to merge**.

## Approvers and Maintainers

[CODEOWNERS](https://github.com/open-telemetry/opentelemetry-go-build-tools/blob/main/.github/CODEOWNERS)

### Become an Approver or a Maintainer

See the [community membership document in OpenTelemetry community
repo](https://github.com/open-telemetry/community/blob/main/community-membership.md).