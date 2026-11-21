# Mtasks Feedback

**The inbox for notes sent from inside the Mtasks app.**

Mtasks is a private, single-user life organiser. This repo has no code. It only holds the
bug reports, ideas and other notes people send from the app, kept as
[GitHub Issues](../../issues).

- **📨 Send to dev team** in Mtasks turns a note into a new issue here. The first line becomes
  the title, and the app adds which device and build sent it.
- The **📨 User submissions** panel in Mtasks lists the open issues, from any copy of the app.
- From that panel a note can be added to the app's dev notes as a bug (**↓ as bug**) or an
  idea (**↓ as idea**), or closed with **✓ Close**, which closes the issue here too.

## How it works

The Mtasks server uses the GitHub command-line tool, `gh`, to create, list and close issues in
`lofty-nz/mtasks-feedback`. `gh` must be installed and signed in on the computer that runs the
server. If it isn't, or if this repo is missing or has Issues turned off, the app shows an
error instead of sending.

## Please note

This repo is public, so anyone can read the issues. Don't put private details in a note:
names, phone numbers, addresses, passwords or anything you wouldn't post online.
