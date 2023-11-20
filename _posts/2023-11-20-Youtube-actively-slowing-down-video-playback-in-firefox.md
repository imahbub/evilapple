---
layout: default
title: "Youtube caught slowing down playback purposefully in Firefox"
permalink: /posts/youtube-caught-slowing-down-playback-purposefully-in-firefox
---
Author: Mahbub Hasan

![Youtube slowing down playback in Firefox](/_posts/ffloading.jpg)
Image: Reddit

A user has noticed that Youtube has pushed a new update that causes firefox to load video significantly slower for no reason. Users that got the update via Youtube's A/B testing and are using Firefox has seen significant load time. And the reason is clear, Youtube has added a new line of code to the updated script that purposefully increases load time for absolutely no reason. 

The code in question is:

```js
setTimeout(function() { c(); a.resolve(1) }, 5E3);
```

A [Reddit user](https://www.reddit.com/user/paintboth1234/) noted that **this chunk of code does nothing except make youtube playback stall the loading for 5 seconds**. Which is quite a noticable time. While I think Youtube will come up with an explanation soon, users see this behaviour as anti-competitive and there should be no such artificial hinderence. 

🌐 Follow the post [here](https://www.reddit.com/r/firefox/comments/17ywbjj/whenever_i_open_a_youtube_video_in_a_new_tab_its/).

---

# Navigations:

🏠 [Home](https://evilapple.org), 📝 [Blog](/pages/blog), 📖 [About this website](/pages/about), 📢 [What are deeds?](/pages/deeds.md)

Social: <a href="https://t.me/The_PenguinsClub">![Static Badge](https://img.shields.io/badge/Telegram-join_us-0088CC?logo=telegram&logoColor=white&link=https%3A%2F%2Ft.me%2FThe_PenguinsClub)</a>

Other projects: <a href="https://the-penguins-club.github.io/bd-blockade/">![Static Badge](https://img.shields.io/badge/The_Penguins_Club%2Fbd--blockade-black?logo=github&logoColor=white&link=https%3A%2F%2Fgithub.com%2FThe-Penguins-Club%2Fbd-blockade)</a>

---

*Copyleft 2023, The Penguins Club*

<script src="https://giscus.app/client.js"
        data-repo="imahbub/evilapple"
        data-repo-id="R_kgDOKvVkrw"
        data-category="General"
        data-category-id="DIC_kwDOKvVkr84CbEw5"
        data-mapping="pathname"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="top"
        data-theme="light"
        data-lang="en"
        crossorigin="anonymous"
        async>
</script>