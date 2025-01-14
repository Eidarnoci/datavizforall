# Embed on your Web
*by [Jack Dougherty, Stacy Lam, and David Tatem](../introduction/who.md), last updated on February 22, 2017*

After you create a chart or map, how do display it inside your website as an *interactive* visualization? Our goal is not a static picture, but a live chart or map that users can explore. This is an important question for beginners, since data visualizations are not valuable unless you can control where and how your work appears. This chapter walks you through the key steps.

First, you need to own a website that supports iframe codes (which we'll explain below). If you do not have a website that supports this, then follow this quick tutorial to [Create a simple web page with GitHub Pages](github-pages). Even if you already have a website, still do this tutorial, because it introduces a tool used many times in this book.

Second, you need to copy the iframe code from your chart or map. An iframe is one line of HTML code with instructions on how to display a web page from a specific address (called a URL). A simple iframe looks like this:
```
<iframe src="https://www.datavizforall.org/embed/index.html"></iframe>
```
No coding skills are necessary, since you're just copying and pasting the iframe, but it helps to be code-curious! Start with a simple example by following this tutorial: [Copy iframe from a Google Sheets chart](iframe-google-sheets/).

Finally, you need to paste (or embed) the iframe code inside your website. Like a picture frame, an iframe allows you to display one web page (your data visualization) inside another web page (your personal website). But unlike a picture frame, where the image is static, an iframe makes content interactive, so visitors can explore the chart or map on your site, even though it may actually be hosted on an entirely different website. Go to this third tutorial, which combines the two steps above, called [Embed iFrame in GitHub Pages](iframe-github).

See more tutorials in this chapter to copy iframes from other visualization tools (such as [Tableau Public](iframe-tableau)) and embed them in other common websites (such as [WordPress](iframe-wordpress), etc.) ** TO DO: add more tutorials and links **

**[Enroll in our free online course](../../enroll)**, which introduces these topics in the brief video below, and offers more exercises and opportunities to interact with instructors and other learners.
{%youtube%}RP1Zg_kbVGQ{%endyoutube%}

{% footer %}
{% endfooter %}
