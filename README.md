# Scala Center Steward

Runs the
[scala-steward-action](https://github.com/scala-steward-org/scala-steward-action)
daily to ensure dependencies across the Scala Center stay up to date.

PRs are sent in by the `scala-center-steward[bot]` app. You can see an example
of what a pr looks like [here](https://github.com/scalacenter/bloop/pull/1893).

## Adding a repo

Edit the [repos.md](./repos.md) file.

**NOTE:** This steward instance is only for `scalacenter` org repos. If you're
outside of the org and would like to run Steward on your repos check out
[diy-steward](https://github.com/armanbilge/diy-steward).
