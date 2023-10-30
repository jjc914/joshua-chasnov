---
title: "This Website"
date: 2023-10-29
lastmod: 2023-10-30T01:11
draft: false
summary: "How I made this website."

showSummary: true
showWordCount: false
---

<style>
  li {
    /* Default bullets style erased */
    list-style: none;
  }

  li::before {
    content: "\2022";
    color: --text-neutral-200;
    display: inline-block;
    width: 1em;
    margin-left: -1em;
  }

  li {
  }
</style>

{{< badge >}}
Web Dev
{{< /badge >}}

This website is statically generated. In the future, I plan on customizing it to add some interesting features, such as embedded 3D scenes with ThreeJS, or even a custom renderer.

The tech stack used for creating this website is:

{{< box cardColor="bg-primary-200 dark:bg-primary-800" textColor="dark:text-neutral-200" >}}
<ul style="padding-top: 0px; padding-bottom: 0px; margin-top: 5px; margin-bottom: 5px; ">
  <li style="padding: 0px; margin: 0px; "> <a href="https://pages.github.com/"><u>GitHub Pages</u></a> for free site hosting. </li>
  <li style="padding: 0px; margin: 0px; "> <a href="https://gohugo.io/"><u>Hugo</u></a> for static site generation. </li>
  <li style="padding: 0px; margin: 0px; "> <a href="https://blowfish.page/"><u>Blowfish</u></a> as the theme. </li>
  <li style="padding: 0px; margin: 0px; "> Vanilla HTML and CSS for everything else. </li>

</ul>
{{< /box >}}

Looking foward to blogging!

{{< github repo="jjc914/joshua-chasnov" >}}