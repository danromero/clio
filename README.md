# clio

![screenshot of Clio theme](screenshot.png)

## What is this?
Jekyll is a template and theme based on [danromero.org](https://danromero.org). This repository is designed to be hosted on [GitHub Pages](https://pages.github.com) with [Jekyll](https://jekyllrb.com). You can read more about the [GitHub Pages + Jekyll integration](https://help.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll). Out-of-the-box the template supports:

1. A homepage that displays a brief introduction and the most recent blog posts in reverse chronological order.
2. An about page located at `/about/`.
3. A sample blog post.
4. An RSS feed for all of the blog posts.

## How to set up

1. Clone the repository.
2. Enable GitHub Pages in the repository's settings.
3. Add future **posts** as Markdown `(.md)` files to the `_posts` folder. GitHub Pages will automatically generate the HTML.
4. Add future **pages** (like the `/about/` page) as Markdown `(.md)` files to the main folder. GitHub Pages will automatically generate the HTML.
5. **Update the images** in the `/assets/` folder. **If you don't, your site will be represented by a purple square.** 🙂
6. Add future images to the `/assets/` folder. 

## Open Graph images
The template is set up to support Open Graph images for services like [Twitter](https://developer.twitter.com/en/docs/tweets/optimize-with-cards/guides/getting-started). Be sure to add the image name in the [front matter](https://jekyllrb.com/docs/front-matter/) of the blog posts and the images should be uploaded to the `/assets/og/` folder. The Hello World! sample post has a functioning example.

## Google Analytics
You can add the Javascript into the `default.html` [layout](https://jekyllrb.com/docs/layouts/) right above the `</body>` tag.

## Why is it called Clio?
[Answer](https://en.wikipedia.org/wiki/Clio).
