# Security policy

## Reporting a vulnerability

Email **security@jspark.app**. Please don't open a public issue, discussion or pull
request for a vulnerability. Until it's fixed, a public report puts everyone who uses
JSpark at risk.

Include what you can:

- The JSpark version and edition (**Settings → About → Copy Diagnostics** copies both,
  with the macOS version and architecture)
- What the problem is and what an attacker could do with it
- Steps to reproduce it, or a proof of concept
- Whether you've told anyone else, and whether you plan to publish

For bugs that aren't about security, write to **support@jspark.app** instead, or use
**Help → Report a Problem…** in the app.

## What to expect

JSpark is made by one person in their spare time, so these are honest targets, not
guarantees.

- **Acknowledgement** within 14 days.
- **An assessment** within 30 days: whether I can reproduce it, how serious I think it
  is, and what happens next.
- **A fix** in a new release as soon as I can. A fix for the engine JSpark runs your
  code on ships within about a week of the upstream fix.
- **Updates** by email while I work on it.
- **Credit** in the release notes, if you want it, once the fix is out.

Please keep the details private until a fix is out, or for 90 days from your report,
whichever comes first. If a fix needs longer, I'll tell you why and we can agree a new
date together.

I don't pay bug bounties.

## Supported versions

Fixes go into a new release only. Older versions are not patched.

Every edition gets security fixes by updating to the latest release: free JSpark and
JSpark+ alike, whether a Yearly plan is renewed, cancelled or refunded.

## Scope

In scope:

- The JSpark app for macOS, as released on this repository's Releases page
- The update feed on `updates.jspark.app`
- The `jspark.app` website

Not a vulnerability in JSpark:

- **Code you run doing what it says.** JSpark isn't a sandbox. A Node.js snippet has
  the same access to your files and network as any program you run. The auto-run pause
  guards against accidents while you type; it isn't a security boundary.
- **Vulnerabilities in npm packages** you install. Report those to the package's
  maintainers.
- **Payments, receipts and License Keys on the store.** Polar runs the checkout. Report
  those to Polar ([polar.sh](https://polar.sh)).
- **Bugs in Electron, Chromium or Node.js** themselves. Report them upstream. If JSpark
  ships a version with a known, serious vulnerability, do tell me.

## Good faith

If you look for vulnerabilities in good faith, follow this policy, don't access or
change other people's data, and give me time to fix what you find, I won't take legal
action against you.
