---
title: SEO| UX - 7 Essentials - A Review
subtitle: SEO and UX are getting increasingly intertwined, and rightly so. My views on 7 such essentials.
cover: \assets\images\seo-7-essentials-post.jpg
coveralt: SEO in colourful alphabets
author: pranesh
category: User Experience
credits: https://unsplash.com/@rxspawn
---
The search-phrase "SEO Essentials" yields a number of results; most people agree on a number of common items, and there are points of disagreement too. I came across an [article](https://dev.to/lampewebdev/top-7-essential-seo-optimizations-for-you-to-learn-in-2019-15i5) on the subject recently. The author makes some good observations and I quote him :

#### The `alt` attribute in `<img>` tags
<br class="my-4">

Images form a large part of modern web design and so this one is rather straightforward and highly recommended by multiple SEO practitioners. The author shares examples and I quote:

<br class="my-2">

>
  - Some bad examples
~~~~
<img src="/dog.png">
<img src="/dog.png" alt="">
<img src="/dog.png" alt="dog">
<img src="/dog.png" alt="animal dog ball red">
~~~~~

>
  - Some good examples
~~~~
<img src="/dog.png" alt="A dog that play with a red ball">
<img src="/billGates.png" alt="Bill Gates, former CEO of Microsoft">
<img src="/123-img.png" alt="Two girls playing on an playground">
~~~~~

<br class="my-2">

The key is to think of the screen-reader users who cant see the image, so describing it as much as possible. Its not easy, when you're coding, your mind is focused often on algorithm and code. I would recommend making the alt tag review a part of your release process, this way you make sure the checkbox gets ticked and at a time when you're thinking less about the code and more about the user.

While this is seems simple, it definitely requires rigour and worth its weight in SEO gold.

<br class="my-4">

#### `<title>` structure

This is a no-brainer. **Titles are critical.**

The author, rather usefully, recommends a length of 60 chars for the title and using the format:

~~~
<head>
    <title>
        Primary Keyword - Secondary Keyword | Brand Name
    </title>
</head>
~~~~

<br class="my-2">

I have a slightly different opinion about this.

  - Without doubt, titles are critical.
  - For discovery, the search engine results are critical, but thereafter, its all about winning on the bookmarks bar, on browser tabs, etc. Hence, IMHO, the first 8 characters are critical. The next part should flow.

I am guilty of preaching without practicing this, and yet awareness is the first step :)

<br class="my-4">

#### `<html lang="varLanguage"` check the language tag in your boilerplates

This can be tricky. While we all know that using the right language is critical, and as the author points out, many boilerplates, templates and frameworks tend to default to `<html lang="en">`

<br class="my-4">

#### Use `rel="nofollow"` on links shared by users

Important, of course, but might not find a place in an SEO essentials list. Sample quote:

> `<a href="http://www.unknown.com/" rel="nofollow">Paid or not trusted content</a>`

<br class="my-4">

#### Use `rel="canonical"` if you have multiple pages with the same content

If you have one of those old websites that has a mobile page, an AMP page and a regular desktop page all of which have the same content, then this is important. Again, not an essential item on my list because who makes Non-Responsive websites anymore?

<br class="my-4">

#### Use `<meta name="viewport"`

As the author rightly points out, not something which directly impacts SEO. Having said that, this would be on my `<head>` essentials list

<br class="my-4">

#### Use media queries

I don't think this is an SEO essentials item, but no doubt an absolutely essential item to consider. I am a fan of the [Bootstrap](https://getbootstrap.com/) framework. However, not an item on my SEO Essentials list.

---
