---
layout: post
title:  "How to setup official controller configration with Steam Input ?"
tags: gamedev steam
categories: gamedev
---

It's a thing that I had to do while updating [Alchemistry](https://store.steampowered.com/app/1730540/Alchemistry/) to be Steam Deck compatible, and [documentation](https://partner.steamgames.com/doc/features/steam_controller) wasn't really helping me, because there are plenty of use cases.

So here we are, here's a small tutorial on how to setup official controller configuration based on your or a community created one.

# Create your configuration (Steam Deck or Big Picture version)

To access controller configuration, click this icon:
![](/assets/img/2022-10-29-deck-edit-config-1.jpg)

Then, edit selected layout (if it doesn't exists, choose your favorite one in templates).
![](/assets/img/2022-10-29-deck-edit-config-2.jpg)

Then, correctly map buttons to game features.
![](/assets/img/2022-10-29-deck-edit-config-buttons.jpg)

At this moment, you can try your configuration locally and check that everything is fine. You can modify configuration in game by pressing the **Steam** button and choosing **controller settings**.

Finally, share the configuration with community:
![](/assets/img/2022-10-29-deck-edit-config-menu.jpg)
![](/assets/img/2022-10-29-deck-edit-config-share.jpg)

Now, everyone can use your configuration. If you want to easily share workshop link (will be useful for future configuration), you can access it using **Layout Details** option.
![](/assets/img/2022-10-29-deck-edit-config-link.jpg)

# Create your configuration (Steam Desktop version)

You can follow the same setps to create a configuration using a steam desktop, to access configuration, open overlay, and click on "Controller configuration".
![](/assets/img/2022-10-29_steam-desktop-overlay.png)

# Set your configuration as official configuration

Go to your **Steamworks Partner** account, then to **App Admin**, then to **Application > Steam Input**. Select your configuration type as "Custom Configuration (Hosted on Workshop)".

![](/assets/img/2022-10-29_steamworks-input-config-type.png)

Then click on **Add custom configuration button** and write your workshop id into the popup.

![](/assets/img/2022-10-29_steamworks-input-config-popup.png)

You can now choose branches you want to apply this configuration for:

![](/assets/img/2022-10-29_steamworks-input-config-settings.png)

And finally you can publish changes. And here we are !

![](/assets/img/2022-10-29_result.jpg)