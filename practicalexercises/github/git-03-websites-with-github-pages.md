# Using GitHub to make a webpage

[[<<PREVIOUS: Cloning and collaborating]](git-02-cloning-and-collaborating) -
[[Table of Contents]](../../index) - [[NEXT: More things to think about>>]](git-04-more-advanced-things-to-think-about)

Still not convinced that GitHub is something you should be using? There's another great feature: They make it relatively straightforward to create a website for free, using [markdown](https://help.github.com/categories/writing-on-github/) and [GitHub pages](https://pages.github.com/). This site is written entirely in Markdown and hosted in GitHub - you can [browse the code yourself](https://github.com/open-source-for-researchers/open-source-workshop), and even fork it or make pull requests.

## Markdown provides formatting on GitHub

You can use it in readme files, tickets, and even to generate websites.

### Some of the formatting options

**bold** text: `**bold**`

_Italic_ text: `_Italic_`

~Strikethrough~ text: `~Strikethrough~`

>Quoted text:

`>Quoted text:`


# Heading 1
## Heading 2
### Heading 3

```
# Heading 1
## Heading 2
### Heading 3
```

```
Code blocks
```

<pre>
```
Code blocks
```
</pre>

 - unordered
 - bullet
 - points


 ```
  - unordered
  - bullet
  - points
 ```


 1. Numbered
 2. Bullets


 ```
 1. Numbered
 2. Bullets
 ```

[Link to another page](http://www.google.com): `[Link to another page](http://www.google.com)`

For a full list, visit [GitHub's Formatting Guide](https://help.github.com/articles/basic-writing-and-formatting-syntax/#styling-text)

## Exercise: Add markdown to your Repository

1. On your computer, create a file in your repository called `index.md`. index is always the entry point to any website - the "Default" webpage.
2. Add some content - perhaps this could be your to-do list or a "Welcome to my homepage" page if you like. Save it and commit it to your repository, then push to GitHub.

### Enabling the website component

Now you need to enable GitHub Pages in order to see it turn into a live website.

1. On your GitHub repository, go to the settings (top rightish tab with a cog icon).
2. Scroll down to the `GitHub pages` section. Under `Source`, select `Master branch` and press save.
3. You can also select a theme if you like!
4. Once this is done, you should see a green message saying "Your site is published at some-link.github.io". Click on it - and ta-da! You have a website.

[[<<PREVIOUS: Cloning and collaborating]](git-02-cloning-and-collaborating) -
[[Table of Contents]](../../index) - [[NEXT: More things to think about>>]](git-04-more-advanced-things-to-think-about)
