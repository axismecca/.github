# Security

## Reporting a vulnerability

Do not open a public issue.

Email [queens@axismecca.com](mailto:queens@axismecca.com) with `SECURITY` in the subject line and include:

- Which module, and which version or commit.
- What the problem is.
- What an attacker could actually do with it.
- The steps to reproduce it, if you have them.

## What happens next

We will confirm we received it within 5 business days. We will tell you whether we agree it is a vulnerability, and if we do, roughly when a fix will land.

Once it is fixed we will publish the fix and credit you by whatever name you want, or not at all if you would rather stay anonymous. Just say which.

If we disagree that it is a vulnerability, we will explain why rather than going quiet.

## Scope

These are tools you download and run on your own machine. Most of them make no network calls at all, and the ones that do say so in their README. The things worth reporting:

- A module executing input it should only be reading.
- Path handling that lets a file be written outside the folder you pointed it at.
- Credentials or API keys getting logged, cached, or written to disk.
- A dependency with a known vulnerability that we are pinning.

Out of scope: axismecca.com and our client sites are not covered here. Those go to the same address, but say which site you mean.

## Supported versions

The current release of each module. We do not backport fixes to older versions. If a fix matters, it ships as a new release.
