The purpose of this repository is to gather together a few bash aliases for speeding up common and repetitive operations with Claude Code on my Linux computer. 

# Context 

I store my Bash aliases at:

~/.bash_aliases

This file is tracked with YADM and auto-pushed every few hours but if we add a few run a quick manual push afterwards.

# Our Workflow

This repo is public because I like to open source. 

I will work with  you to come up with bash aliases. 

Bash aliases, as you know, are very simple: but it's important that they don't conflict with other commands and also important that they be memorable: so I might provide a pattern that we're using to work with. 

Here's how we'll work step by step:

## 1: Agree on the alias(es)

I usually create aliases in batches but might do so one by one if I find a particular need. 

I'll ask you something like "Let's add a bash alias for seeding ./claude/commands at the pwd. I'm thinking addcomandstothisdir."

You might respond: "Sure. But that's a bit clunky! How about just commandshere?"

I might respond: "great! Create that!"

You would then:

1: Create the bash alias by adding it to ~/.bash_aliases

2: Create a markdown file in this repo (at aliases). Heading: Alias function (like # Add Slash Commands Directory In PWD); then the bash alias in a codefence.

That would wrap up the task. 

---

# Backfilling This Repo

Workflow 2 is backfilling this repo: sharing the Claude Code specific aliases I've already created inmy bash aliases file.

For this:

- Scan my bash aliases and identify Claude Code specific ones (only) 
- If they're not already here, copy them into the aliases folder. 