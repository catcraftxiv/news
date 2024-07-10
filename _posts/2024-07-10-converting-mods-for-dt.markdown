---
layout: post
title:  "Converting mods for Dawntrail's test version of Penumbra"
date:   2024-07-10 12:04 +0300
---

With Penumbra test version released yesterday, you can use mods  through it again, but if you will try to import mod that was made before Dawntrail release you might find it all weird and broken, thats cause Penumbra does **not** convert them automatially for Dawntrail <:c But fear not, cause TexTools does! 

All you need to do is import your mod into TexTools, then you can export it back right away and it will work fine in new Penumbra :> I will write how to do that step by step if you had not used TexTools v3 yet!

If you are into modding, you might want to [convert your entire penumbra mod folder](#converting-your-entire-penumbra-mod-folder)! Please don't do advanced stuff if you are not familiar with it :>



## Step by Step Guide

This is only convert working mods like gear so test penumbra can use it, it will **not** fix really broken mods like sculpts!

> ### MAKE SURE SET SAFE MODE

If you dont have TexTools installed yet, then [get it here](https://www.ffxiv-textools.net/)! After launching it, you will see its main window

<figure>
    <img class="img-modal" src="{{ site.baseurl }}/assets/img/posts/converting-mods-for-dt/textools-main-window.png" style="width:100%" alt="main window">
  	<figcaption>
		make sure it says SAFE at top right
	</figcaption>
</figure>

Safe mode means changes you are making inside textools will not be actually applied to your game files! After that, click on "Transaction Status: Closed" at the top right corner, then "BEGIN TRANSACTION" and close new window appeared. Now button should says  "Transaction Status: Open"

<figure>
    <img class="img-modal" src="{{ site.baseurl }}/assets/img/posts/converting-mods-for-dt/pic2.png" style="width:100%" alt="trasaction open">
    <figcaption>
		transaction open
	</figcaption>
</figure>

While transaction is open it store every changes you made ready for export, so you dont need to select files you want to export manually. Transaction also not saved anywhere until you commit it, so not close textools if you are not done with it! Now click "Mods > Import ModPacks" in the top menu and install mod as usual :> If your mod have few options or versions, then make sure to tick options as you want to see it in game! After import is done, click on Transaction Status button again and you will see window now get some files in it!

<figure>
    <img class="img-modal" src="{{ site.baseurl }}/assets/img/posts/converting-mods-for-dt/pic3.png" style="width:100%" alt="transaction window">
    <figcaption>
		commiting transaction
	</figcaption>
</figure>

Select "Transaction Target" PMP or TTMP, which file type you want to get on export, then select TARGET PATH where to export, and button COMMIT TRANSACTION will became active! 

After commiting transaction it will export mod and clearing every changes during transaction from textools, so you can convert next mod by beginning new transaction!

## Converting your entire Penumbra mod folder

If you are not that much into technical part of modding and errors, i recommend you not doing that and just wait until penumbra will be able to do that automatically for you :>

> #### *keep backups just in case*



1. join [Penumbra & Glamourer Discord server](https://discord.gg/kVva7DHV4r)
2. see [#questions-penumbra chaneel pinned messages](https://discord.com/channels/884363610640498698/968591485060677653/1260361656677171291)