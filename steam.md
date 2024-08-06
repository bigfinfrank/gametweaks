# Steam Client Tweaks

These are tweaks for the steam client itself, not any specific game, but they all affect your Steam games/your general interaction with Steam.


## 1. Launch Options

Replace the target in all `Steam.lnk`s (shortcuts) with the following:

```cmd
"C:\Program Files (x86)\Steam\steam.exe" -console -dev -fulldesktopres -offlinemode --showallbetas -silent -testbutton
```

These are all mostly self explanatory, but you can see xPaw's dump of steam commands [here](https://gist.github.com/xPaw/fe7d275d31da14d70481) which includes some more info.


## 2. π🐀

I have multiple accounts. I have family sharing on between those accounts. Some games *cough black ops 3 cough* will not allow me to use the DLCs owned by the primary account, despite already being downloaded and being able to play the normal game.

[Yar har, fiddle de dee
Being a pirate is alright to be
Do what you want 'cause a pirate is free
You are a pirate!](https://github.com/pointfeev/CreamInstaller)

## 3. Adding all free DLCs for your owned games to your account

1. This will make your game installs take up more storage and your downloads take longer. I have 4TB of NVMe drives and 8gig symmetrical internet, so I don't care, but you might.

2. Go to https://steamdb.info/freepackages/?no_filters=1 and follow the instructions in the "How to use this?" section.

4. Next to "If you want to only view content for your owned games", click "click here to only show these".

5. CLick "Activate these packages now" and leave the browser tab open for a few hours, you'll only be able to activate 50 per hour.


## 4. Cheaper steam games **(not just with Steam Keys)**

Obviously you can check third party grey-market sites like G2A for Steam keys when buying your games, however there's a better way.

It's arguably against Steam ToS and might be considered tax evasion in certain jurisdictions, but realistically Steam doesn't enforce it past prevention and your government likely wouldn't find out and if they did, because of how significantly cheaper (typically 50-95%) games are, even on a [$1000 bundle](https://steamdb.info/bundle/6465) you'll only be paying tax on $50 which comes out to less than a dollar. You'll be able to afford to just pay them what you owe.

I have a secreted gist with instructions on how to make a fresh account with the region locked, but the concept is very similar for changing the region of your primary account if you don't want to mess around with family sharing. You can find the gist [here](https://gist.github.com/bigfinfrank/363d5730f52f5f7483c1774ffdeb5742), for changing the region you'll need to do step 2 and then steps 8 onward, the rest won't really apply.


## 5. Steam Account security & Safety

I have a gist on this topic as well, it's fairly all-encompassing and you can find it [here](https://gist.github.com/bigfinfrank/a044627149d24b774dfc5bd92b4a4cf8)
