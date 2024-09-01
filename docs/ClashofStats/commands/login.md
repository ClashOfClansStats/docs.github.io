---
title: Login
layout: default
nav_order: 1

has_toc: false
parent: Commands
grand_parent: Discord Bot
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
<image src="https://raw.githubusercontent.com/ClashOfClansStats/docs.github.io/0c34f664b3b703e923487aaf93361079322d1112/images/commands/login/clashaddbase.png"
style="border-radius: 15px;
max-width: 120%;
max-height: 120%;
box-shadow: 10px 5px 5px #212123;">
</image>

The {PlayerTag} will be stored in a SQLite database called 'storage.db' to be accessed in the future.

---

# Disconnect a Clash of Clans Base

In a server where the bot is active, type this commands
<image src="https://raw.githubusercontent.com/ClashOfClansStats/docs.github.io/ae07eb65a2e0126c1577334ddab3ab5f9dce0d48/images/commands/login/clashrembase.png"
style="border-radius: 15px;
max-width: 120%;
max-height: 120%;
box-shadow: 10px 5px 5px #212123;">
</image>

The {PlayerTag} will be removed from the database

---

# Connect a Clash of Clans Clan

In a server where the bot is active, type this commands
```
/clashaddclan {ClanTag}
```

The {PlayerTag} will be stored in a SQLite database called 'storage.db' to be accessed in the future.