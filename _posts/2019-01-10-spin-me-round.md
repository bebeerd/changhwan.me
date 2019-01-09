---
layout: post
title: Spin me round
date: 2019-01-10 03:04:03 +0900
---

{% include youtube.html width=50 height=35 url="https://www.youtube.com/embed/PGNiXGX2nLU?start=61" %}

Yes, I know that. This song hits the internet a long time ago, so if you don't know this song, congratulations, you are young enough.

So do you wonder why I am mentioning this song?

Ha, did you noticed this website's logo is spinning when you scroll? Unless you are on a mobile phone, you can see that by scrolling this website up and down.

Yep. I am always looking for fun. And no matter what you think, I have enough fun by spinning logo like this.

Anyway, here's some code.

```javascript
(function() {
    function rotate() {
        var deg = window.scrollY % (360 * 4) / 4;
        var elem = document.getElementById("drink");

        elem.style.transform = 'rotate(' + deg + 'deg) perspective(0)';
    }

    window.addEventListener('scroll', rotate);
})();
```

You can use this code on your website if you have things you want to spin, 'right' round or not. 🙃

Oh, and if you like the song? Did you recognize that intense, addictive part as I am?

Here it is.

{% include youtube.html width=50 height=35 url="https://www.youtube-nocookie.com/embed/ZKV4GZTmfGM" %}

(I don't care what you think, but yes, I think you are strange. 🤪)
