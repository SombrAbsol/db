---
author: DS-Homebrew
avatar: https://avatars.githubusercontent.com/u/46971470?v=4
categories:
- utility
- save-tool
color: '#be8345'
color_bg: '#80582e'
created: '2018-10-02T16:59:38Z'
description: 'GodMode9i Explorer - A full access file browser for the Nintendo DS
  and DSi consoles :godmode:'
download_page: https://github.com/DS-Homebrew/GodMode9i/releases
downloads:
  GodMode9i.7z:
    size: 356397
    size_str: 348 KiB
    url: https://github.com/DS-Homebrew/GodMode9i/releases/download/v3.4.0/GodMode9i.7z
  GodMode9i.cia:
    size: 966912
    size_str: 944 KiB
    url: https://github.com/DS-Homebrew/GodMode9i/releases/download/v3.4.0/GodMode9i.cia
  GodMode9i.dsi:
    size: 952320
    size_str: 930 KiB
    url: https://github.com/DS-Homebrew/GodMode9i/releases/download/v3.4.0/GodMode9i.dsi
  GodMode9i.nds:
    size: 952320
    size_str: 930 KiB
    url: https://github.com/DS-Homebrew/GodMode9i/releases/download/v3.4.0/GodMode9i.nds
github: DS-Homebrew/GodMode9i
icon: https://db.universal-team.net/assets/images/icons/godmode9i.png
image: https://raw.githubusercontent.com/DS-Homebrew/GodMode9i/master/resources/logo2.png
image_length: 44248
layout: app
license: gpl-3.0
license_name: GNU General Public License v3.0
nightly:
  download_page: https://github.com/TWLBot/Builds/blob/master/extras/GodMode9i.7z
  downloads:
    GodMode9i.7z:
      url: https://github.com/TWLBot/Builds/raw/master/extras/GodMode9i.7z
qr:
  GodMode9i.cia: https://db.universal-team.net/assets/images/qr/godmode9i-cia.png
  GodMode9i.dsi: https://db.universal-team.net/assets/images/qr/godmode9i-dsi.png
  GodMode9i.nds: https://db.universal-team.net/assets/images/qr/godmode9i-nds.png
source: https://github.com/DS-Homebrew/GodMode9i
systems:
- DS
title: GodMode9i
update_notes: '<h3 dir="auto">What''s new?</h3>

  <ul dir="auto">

  <li>DSi NAND is now accessible after a DS flashcard has been booted with unlocked
  SCFG!

  <ul dir="auto">

  <li>Files can now be copied across all drives with all flashcards!</li>

  <li>Requires a DSi BIOS dump in <code class="notranslate">sd:/_nds/</code>. Either
  a full or part dump (of which is already dumped by TWLMenu++ to said location) will
  work.</li>

  </ul>

  </li>

  <li>Bootstrapping a <code class="notranslate">.nds</code> file has been removed.
  This is due to:

  <ul dir="auto">

  <li>TWLMenu++ already having such feature.</li>

  <li>GM9i not being updated as often.</li>

  <li>Would run into the same issue as TWLoader, where we''d maintain more than one
  <code class="notranslate">.nds</code> loader.</li>

  </ul>

  </li>

  <li><a class="user-mention notranslate" data-hovercard-type="user" data-hovercard-url="/users/metroid-maniac/hovercard"
  data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="https://github.com/metroid-maniac">@metroid-maniac</a>:
  Added dumping GBA RTC data in metadata and saves.</li>

  </ul>

  <h3 dir="auto">Bug fix</h3>

  <ul dir="auto">

  <li><a class="user-mention notranslate" data-hovercard-type="user" data-hovercard-url="/users/Epicpkmn11/hovercard"
  data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="https://github.com/Epicpkmn11">@Epicpkmn11</a>:
  Fixed dumping apps with versions over <code class="notranslate">000000FF</code>.</li>

  </ul>'
updated: '2023-01-01T07:13:38Z'
version: v3.4.0
version_title: 'v3.4.0: New Year, New Release'
website: https://wiki.ds-homebrew.com/godmode9i/
wiki: https://wiki.ds-homebrew.com/other/godmode9i
---
### Installation:
- TWiLight Menu++: Use either the `GodMode9i.nds` or `GodMode9i.dsi` file, they function identically with TWiLight Menu++
   - The only difference is that `GodMode9i.dsi` has a Title ID
- Flashcard: Use the `GodMode9i.nds` file
- hiyaCFW SDNAND: Install the `GodMode9i.dsi` file with [TMFH](/ds/tmfh)
- 3DS HOME Menu: Install the `GodMode9i.cia` file with [FBI](/3ds/fbi)

### Features:
- Dump GameBoy Advance cartridges on the original Nintendo DS and Nintendo DS Lite consoles.
- Dump Nintendo DS/DSi cartridges on Nintendo DSi and Nintendo 3DS consoles (if GodMode9i is ran on the console SD card).
- Copy, move, delete, rename files/folders and create folders.
- Mount the NitroFS of .nds files.
- Browse files on supported flashcards when running GM9i from the NAND or SD Card. (`AceKard 2(i)` & `R4 Ultra (r4ultra.com)`)