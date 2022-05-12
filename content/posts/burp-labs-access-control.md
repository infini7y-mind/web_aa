---
title: "Burp Labs - Access Control"
date: 2022-05-12T01:41:25+01:00
showDate: true
draft: false
tags: ["writeup"]
---

Started doing Burp Suite a while ago and now started with their own labs.

Academy link => [here](https://portswigger.net/web-security)

Access Control Labs link => [here](https://portswigger.net/web-security/access-control)

&nbsp;

# Access Control
So... what is access control?

Have you ever seen any type of button in any kind of platform that simply was greyed out because you didn't have permission to use it?

Well, that's due to the access controls.

They *control* who has *access* to what... that's it! Super hard right? x)

&nbsp;

## Lab #1 (Apprentice level)
Most websites are built pretty much in the same way for easier dev maintenance and to cope with all the shenanigans search engines (like Google, Bing,...) require to index the website data.

And in most cases the structure of privileged access looks like

```
https://website.com/admin
```

or has some info stored in the robots.txt file

```
https://website.com/robots.txt
```

In this lab's particular case you should see the robots.txt file ;)

&nbsp;

## Lab #2 (Apprentice level)
As the above practice became too popular, web developers became worried about security aspects of it (as they should) and began to try to conceal that information by setting up a less predictable URL.

Thing is that most of devs think hackers can't code xD

So the solution many times passed by constructing the webpage info based on the user with scripts inside the webpage itself.

That's the case of this lab. You should see in the middle of a JavaScript <script> the amin page you want.
