# Webdeck Player Vertical Version

This project is a modified version of the original Web Deck Player created by @cristiancfm
All credit for the original concept and implementation goes to the original author.

**Please go to check the original project:** https://github.com/cristiancfm/webdeck-player

**Support Chris here:**
<br><a href="https://ko-fi.com/cristiancfm"><img src="https://storage.ko-fi.com/cdn/kofi2.png?v=6" alt="ko-fi" height="35"/></a>

# About this version

<img width="310" height="427" alt="Webdek vertical default" src="https://github.com/user-attachments/assets/aaa58308-7e01-4556-8c0d-6b028b2ee5f5" />
<img width="302" height="430" alt="Webdek vertical minimal" src="https://github.com/user-attachments/assets/90894038-9899-45a7-94c6-9b342e56a3d7" />

- **_Default_ and _minimal_ themes were modified to have a vertical layout**


    This player is designed to run inside a **vertical container of 280x400px**.
    It can be used in two ways, as mentioned in the original project:
    
    1. You can open the player in a separate browser window, allowing users to keep navigating your site while the music continues playing.
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
    2. Embed the player using an iframe.
        ```html
        <iframe
        src="/webdeck-player/index.html"
        height="400"
        width="280"
        scrolling="no"
        style="border: none;"
        ></iframe>
        ```
