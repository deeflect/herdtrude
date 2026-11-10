# Herdtrude: one window for all your coding agents

[Herdtrude](https://herdtrude.app) is a Mac app for people who run coding agents. It shows every session on all your machines in one window and tells you which agent needs you. It costs $49, paid once, and covers every Mac you own.

This repository has no source code. It is the product's public page on GitHub, and bug reports and feature requests go in its Issues tab.

## What it does

- Herdtrude draws each session as a sheep, and the sheep's face shows the state: working, thinking, needs you, done, error or idle.
- When an agent stops to ask, a menu-bar sheep, a corner pet with Allow and Deny, an alert that names the session and an optional sound tell you which one.
- You can add a Mac or a server over SSH. Its sessions join the sidebar, grouped by machine and project, and keep running when you quit the app.
- Quota for every Claude, Codex, Cursor and Antigravity account sits side by side with its reset time, and you can switch between accounts in one click.
- Insights show tokens per agent, per machine and per day, what they would cost at API prices, and a burn rate that tells you whether the week's quota will last.
- Files, line numbers, URLs and commit hashes in agent output become links. Hover to peek, or Command-click to open your editor at the line.
- Each agent can get its own git worktree, and a command-line tool with --json output lets you script the herd.

## Requirements

You need a Mac. Any server or second Mac you add must be reachable over SSH.

## Get it

Buy and download Herdtrude for Mac from the Herdtrude site. The price is $49 once, for every Mac you own.

## Questions

### Which coding agents does Herdtrude work with?

Claude Code, Codex, Cursor, Antigravity and OpenCode. The quota view covers Claude, Codex, Cursor and Antigravity accounts.

### Can Herdtrude watch agents on my other machines?

Yes. You add a Mac or a server over SSH, and pairing installs the SSH keys.

### Is there an iPhone app?

Not yet. An iPhone app that pairs by QR code is listed as coming soon.

### What is Herdtrude built on?

Herdtrude is built on Herdr, an open-source engine. Herdr is the upstream project.

## Made by

Herdtrude is made by [Dee (deeflect)](https://deeflect.com), a one-person studio.
