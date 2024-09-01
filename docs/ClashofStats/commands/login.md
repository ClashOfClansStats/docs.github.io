---
title: Login
layout: default
nav_order: 1

has_toc: false
parent: Commands
grand_parent: Clash of Stats
---

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

# Connect a Clash of Clans Base

In a server where the bot is active, type this commands
```
/clashaddbase playertag:{PlayerTag}
```
The {PlayerTag} will be stored in a SQLite database called 'storage.db' to be accessed in the future.

# Disconnect a Clash of Clans Base

In a server where the bot is active, type this commands
```
/clashrembase
```