# hoard-releases

Public release channel for Hoard. Binaries only.

## Welcome to the mancave

Boys. You have been drafted as testers. This is the way.

Hoard is a money app that runs on your own PC. It reads the bank alert emails you already get, sorts every charge, and turns your budget into a goblin RPG. Your money data never leaves your machine. No account, no cloud, no ads, because the whole point is that nobody else gets to see it.

The current build is v1.6.2. It ships with 5,072 unit tests and 17 more that run against the packaged app, because there was nobody else to catch it. Now there is. That's you.

## Install it

1. Open the [latest release](https://github.com/Jordunkelly/hoard-releases/releases/latest).
2. Download `Hoard.Setup.exe`. It is about 275 MB.
3. Windows will say it protected your PC. The installer is not signed yet. Click More info, then Run anyway. Trust me bro.
4. It installs and opens on its own.

Windows only for now. Mac bros, press F.

## Updates

Hoard asks GitHub for a new version every ten minutes while it is open. When there is one, a badge shows up in the sidebar. Click it. Hoard closes, swaps itself out, and comes back.

If it does not come back, download the newest `Hoard.Setup.exe` from here and run it once. The old updater could quit and never return. Task failed successfully. The fixed one takes over after your next update.

## What I need from you

* Break it. Click everything twice.
* Tell me what confused you. If you had to ask, it is a bug.
* Screenshots or it didn't happen.
* Settings, Data, Export diagnostics saves a file with your version and the logs. Look it over, then send it to me in the group chat.

A message that just says "it's broken" gets you nothing. Sir, this is a Wendy's. Tell me what you clicked.

## FAQ

**Does it need my bank password?**
No. It never logs into your bank. It reads the alert emails your bank already sends. It needs an app password for that mailbox, and it keeps it encrypted on your PC.

**Does it phone home?**
Barely. It talks to your own mailbox, obviously. Every ten minutes it asks GitHub if there is a new version, which sends your IP address and nothing else. You can turn that off in Settings, Data, Privacy. If you say yes to merchant icons during setup, it asks DuckDuckGo for each shop's logo once. That's the whole list.

**Is it free?**
For you, yes. It's free real estate.

**Why goblins?**
Stonks go up when the goblin hoards.

**ELI5**
You spend money. Your bank emails you. Hoard reads the email. The goblin gets gold when you behave.

Edit: thanks for the gold, kind stranger. It is in the app.
