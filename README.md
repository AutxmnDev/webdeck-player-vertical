# Webdeck Player – Vertical Layout

This project is a modified version of the original **Webdeck Player** created by **@cristiancfm**
All credit for the original concept and implementation goes to the original author.

**Please go to check the original project:** https://github.com/cristiancfm/webdeck-player

**Support Chris here:**
<br><a href="https://ko-fi.com/cristiancfm"><img src="https://storage.ko-fi.com/cdn/kofi2.png?v=6" alt="ko-fi" height="35"/></a>


---

## About this version

This version adapts the original Webdeck Player to a **vertical format**.

<img width="611" height="427" alt="webdeck player vertical" src="https://github.com/user-attachments/assets/c0a37c96-e0bd-4bbe-8d10-3192d1261f14" />

### Changes in this version

- Vertical layout **280x400px**
- Modified **Default** and **Minimal** themes for vertical use

---

## Installation

1. Download the project from the Releases page or clone the repository
2. Copy the ```webdeck-player-vertical``` folder into your project

## Usage

This player is designed to run inside a **280x400px vertical container**.

You can use it in two ways, as in the original project:
### 1. Open in a new browser window
```html
        <button
         onclick="window.open(
         '/webdeck-player/index.html',
         'Vertical Web Deck Player',
        'height=400,width=280'
        )"
        >
         Open Web Deck Player
        </button>
```

### 2. Embed the player using an iframe

```html
        <iframe
        src="/webdeck-player/index.html"
        height="400"
        width="280"
        scrolling="no"
        style="border: none;"
        ></iframe>
```
---

## Adding playlists

Go to the ```script.js``` file inside the ```webdeck-player-vertical``` folder. There you can follow the instructions to change the playlists shown in the player.

## Adding themes

To add a new theme to the player, copy its folder to the themes folder. Then, open the ```script.js``` file and add it to the list following the instructions inside.

## Creating a new theme
Themes are just a collection of resources (like images or fonts) and a CSS file to modify the player appearance. You just need basic knowledge about CSS to start! Create a new theme following these steps:

1. Inside the ```webdeck-player-vertical``` folder, locate the themes folder and open it.
2. Choose a theme folder as a base, for example, the default theme. You can modify any other theme.
3. Duplicate your chosen folder and rename it. For example, call it ```my-theme```.
4. Add your new theme to the ```script.js``` file following the instructions inside it.
5. Inside your theme folder, open the ```webdeck-player.css``` file and modify it to your liking. You can also change the fonts and the images. Do not rename any image. Their paths are used in the ```script.js``` file. The ```about.txt``` file is for adding a description about the theme and your name.

## Credits
Created by Chris. Vertical modification by Autxmn. Licensed under the MIT License. Some components of the software such as fonts were created by others. In these cases, attribution was given for their work.
