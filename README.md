# sid.wifi.creates Quartz Website

Personal website and blog for projects, articles and other thoughts. Currently hosted using github pages at [https://ctrlbadger.github.io/quartz/](https://ctrlbadger.github.io/quartz/)

## How was this made?

This website is made using the excellent [Quartz](https://github.com/jackyzha0/quartz) project, a static site generator for markdown pages designed for [Obsidian](https://obsidian.md/) notes.

This wesite is (hopefully) constantly being updated!

## How I make changes and additions

- Inside my Obsidian vault is a symlinked folder pointing to the `content` folder of the repository. This holds all the markdown pages for my website.
- I've placed a batch script inside a note that runs `npx quartz update`. I run this whenever I've made changes.

## Possible Updates

- Fix the date created attributed. Currently displays last sync date on all notes.
- Add [Folk-Tune-Notes](https://github.com/ctrlbadger/Folk-Tune-Notes) in some way. Create a way of displaying Folk Tunes in `abc` format.
