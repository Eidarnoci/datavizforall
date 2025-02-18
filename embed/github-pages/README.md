# Create a Simple Web Page with GitHub Pages
*by [Jack Dougherty](../introduction/who.md), last updated February 22, 2017*

Question: After you create an interactive chart or map, how do you embed the live version in a website that you control?

The full answer requires three steps:
1) Create a web page that supports iframe codes
2) Copy the iframe code from your visualization
3) Embed (or paste) the iframe code into your web page

This tutorial focuses on the **first step**. If you don't already have your own website, or if you are not sure whether your site supports iframe codes, then follow the steps below. We will create a simple web page with a free and friendly tool called GitHub (http://github.com), and host it on the public web with the built-in GitHub Pages feature. For **steps 2 and 3**, see the [Copy iframe from Google Sheets](../iframe-google-sheets) tutorial and the [Embed iFrame in GitHub Pages](../iframe-github/) tutorial in this chapter.

## Tool Review
GitHub (http://github.com) is a versatile tool that can be used to create simple web pages.
- Pros:
  - Free and easy-to-learn tool to edit and host simple pages on the public web.
  - All steps below can be completed in your web browser.
- Cons:
  - All work on GitHub is public by default. Private repositories (folders) require payment.
  - New users sometimes confuse the links for code repositories versus published web pages.

## Video tutorial and step-by-step instructions
{%youtube%}AFdogZFyN0c{%endyoutube%}

1) Sign up for free GitHub account, then sign in, at http://github.com.
2) Create a new repository (also called a "project" or similar to a "folder").
3) Name your repository (or "repo"), and select Initialize with a README file. Optional steps: add a description and select a license.
4) Scroll down and click the green button to Create your repo, which will appear in a new browser tab, with this URL format:
```
https://github.com/YOUR-USERNAME/YOUR-REPO-NAME
```
5) In your GitHub repo, click on Settings, scroll down to GitHub Pages, select Master branch as your source, then Save. This publishes the code from your repo to the public web.
6) When the Settings page refreshes, scroll back down to GitHub Pages to see the new link to your published website, which will appear in this format:
```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME
```
7) Right-click and Copy the link to your published web site.
8) At the top of the page, click on the repo name to return to the main level.
9) Click the README.md file to open it in your browser, and click the pencil symbol to edit it.
10) Inside your README.md file, paste the link to your published web site, and type any text you wish to appear. The .md extension refers to Markdown, an easy-to-read computer language that GitHub Pages can process.
11) Scroll down and click the green Commit button to save your edits.
12) When your GitHub repo page refreshes, click on the new link to go to your published web site.
**BE PATIENT!** Your new site may not appear instantly. Refresh the browser every 10 seconds. You may need to wait up to 1 minute for a new site to appear the first time, but later changes will be much faster.

Remember that GitHub Pages is designed to create simple web pages and sites. See other web publishing tools mentioned in this chapter to create more sophisticated web sites.

{% footer %}
{% endfooter %}
