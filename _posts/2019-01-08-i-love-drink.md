---
layout: post
title: I love drink
date: 2019-01-08 02:56:43 +0900
---

You may think that I am an alcoholic, but I'm not. Yes, I love drinking, but I am not addicted to it. Loving something and being addicted to it is entirely different. Actually, the word "drink" I use means not only drinking alcohol but also drinking water, drinking tea, drinking coffee, etc. The feeling of cold liquid moving through the throat, that's what I love so much.

Anyway, I love drink so much, so I decided to use every drink emoji as the logo of my website.

It was too easy to find every drink emoji. Actually, it was too easy to see every emoji. The Unicode Consortium has a full list of emoji, and they grouped all emoji with their relations. So, you can find every drink emoji here. <https://unicode.org/emoji/charts/emoji-list.html#drink>{:target="_blank"}

There are 14 emoji related to a drink. And I removed first one, which is 🍼(baby bottle) because I don't drink baby milk anymore. 😊

So I wrote this simple code.

```javascript
(function() {
    var emojis = [
        '🥛', '☕️', '🍵', '🍶', '🍾', '🍷', '🍸', '🍹', '🍺', '🍻', '🥂', '🥃', '🥤',
    ];

    (function update() {
        var emoji = emojis[Math.floor(Math.random() * emojis.length)];
        document.getElementById("drink").innerHTML = emoji;
        setTimeout(update, 10 * 1000);
    })();
})();
```

And I felt satisfied.

👼

Ah by the way, I like beer most among alcohols, especially [Pilsner Urquell](https://en.wikipedia.org/wiki/Pilsner_Urquell){:target="_blank"} and [Kilkenny](https://en.wikipedia.org/wiki/Kilkenny_(beer)){:target="_blank"}. Don't worry. You can be my friend if you don't like these.

I love drink. You know that 👍
