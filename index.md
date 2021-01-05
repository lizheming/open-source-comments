# Open-source self-hosted comments for a static website

This comparison table is inspired by
[staticsitegenerators.net](http://staticsitegenerators.net/). Contribute at
[github](https://github.com/pozitron57/open-source-comments) —
add the missing data. Github-related data (stars, open issues + PR, etc.)
are updated daily automatically. Want different columns? Noted a bug? Submit
an [issue](https://github.com/pozitron57/open-source-comments/issues/new).

## What’s wrong with Disqus

Disqus loads absurd amount of tracking services, which exposes your visitors’
personal data and significantly increases loading time. See, e.g., 
[this post](http://donw.io/post/github-comments/#what-s-wrong-with-disqus).

## What’s not covered here

For a static website, one usually wants a lightweight commenting server with
as little dependencies as possible. Few commenting engines listed on the page
are provided by heavy applications (e.g.,
[discourse](https://github.com/discourse/discourse),
[talkyard](https://github.com/debiki/talkyard)), but the majority are
relatively lightweight applications designed specifically to provide 
comments for the static pages.

This page prioritizes information on self-hosted comments. However, there
are other open-source solutions, including implementations of third-party
services (e.g., Github issues, such as
[[1]](https://github.com/imsun/gitment),
[[2]](https://github.com/gitalk/gitalk),
[[3]](https://github.com/Blankj/awesome-comment),
[[4]](https://github.com/utterance/utterances)).

There are also [dokieli](https://github.com/linkeddata/dokieli) and
[hypothesis](https://web.hypothes.is/), that provide annotation-like
functinality.

Also, there is an
[echo-chamber](https://github.com/tessalt/echo-chamber-js).

>When a user submits a comment, echochamber.js will save the comment to the
>user's LocalStorage, so when they return to the page, they can be
>confident that their voice is being heard, and feel engaged with your very
>engaging content. It does not make any HTTP requests. Since LocalStorage
>is only local, you and your database need not be burdened with other
>people's opinions.

## Stars vs. time
The figure below shows some of the top competitors except for Discourse (as
it's not just a light commenting server like others). The figure is useful to
indirectly estimate how active the project is.

<a href="stars-v-date.png">
<img src="stars-v-date.png" alt="Plot stars vs. time" width="800px" />
</a>

## Choose columns to show

## Share your experience

Please share your experience if you are using one of the commenting systems
listed in the table. Write a short summary and provide your "Likes" and
"Dislikes" to help others to decide which commenting system suits them
best.
