---
layout: page
title: Teaching
permalink: /teaching/
---

<style>
  .no-border, .no-border td, .no-border th {
    border: none;
      background-color: white;
  }
  table {
   border-collapse: collapse;
}

table tr, table td, table th {
   border: none;
}
</style>

<table class="no-border">
  <tr>
    <td>ABC</td>
    <td>XYZ</td>
  </tr>
  <tr>
    <td>Cell 3</td>
    <td>Cell 4</td>
  </tr>
</table>



<style>
.content {
  display: flex;
  align-items: center; /* This is optional and aligns the image and text vertically */
}

.content-image {
  margin-right: 20px; /* Add some space between the image and the text */
  width: 150px;  /* Set the width of the image */
  height: auto;  /* This makes the image height adjust to the width while maintaining the aspect ratio */
}

.content-text {
  flex-grow: 1; /* Allows the text to take up any remaining space */
}
</style>

<div class="content">
  <p class="content-text">
    This is a paragraph of text that will appear beside the image.This is a paragraph of text that will appear beside the image.This is a paragraph of text that will appear beside the image.This is a paragraph of text that will appear beside the image.This is a paragraph of text that will appear beside the image.This is a paragraph of text that will appear beside the image.This is a paragraph of text that will appear beside the image.This is a paragraph of text that will appear beside the image.This is a paragraph of text that will appear beside the image.This is a paragraph of text that will appear beside the image.This is a paragraph of text that will appear beside the image.This is a paragraph of text that will appear beside the image.This is a paragraph of text that will appear beside the image.This is a paragraph of text that will appear beside the image.This is a paragraph of text that will appear beside the image.This is a paragraph of text that will appear beside the image.
  </p>
    <img src="/images/image.jpg" alt="description" class="content-image" />
</div>



### Step 1) Fork Reverie to your User Repository

Fork [this repository](https://github.com/amitmerchant1990/reverie), then rename the repository to `yourgithubusername.github.io`.

Alternatively, you can use [Use this template](https://github.com/amitmerchant1990/reverie/generate) button if you want to create a repository with a clean commit history which will use Reverie as a template.

Your Jekyll blog will often be viewable immediately at <https://yourgithubusername.github.io> (if it's not, you can often force it to build by completing step 2)

### Step 2) Customize and view your site

Enter your site name, description, avatar and many other options by editing the `_config.yml` file. You can easily turn on Google Analytics tracking, Disqus commenting and social icons here.

Making a change to `_config.yml` (or any file in your repository) will force GitHub Pages to rebuild your site with jekyll. Your rebuilt site will be viewable a few seconds later at <https://yourgithubusername.github.io> - if not, give it ten minutes as GitHub suggests and it'll appear soon.

### Step 3) Publish your first blog post

Create a new file called `/_posts/2019-2-13-Hello-World.md` to publish your first blog post. That's all you need to do to publish your first blog post! This [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) might come in handy while writing the posts.

> You can add additional posts in the browser on GitHub.com too! Just hit the <kbd>Create new file</kbd> button in `/_posts/` to create new content. Just make sure to include the [front-matter](http://jekyllrb.com/docs/frontmatter/) block at the top of each new blog post and make sure the post's filename is in this format: year-month-day-title.md

## Using Categories in Reverie

You can categorize your content based on `categories` in Reverie. For this, you just need to add `categories` in front matter like below:

For adding single category:

```md
categories: JavaScript
```

For adding multiple categories:

```md
categories: [PHP, Laravel]
```

The contegorized content can be shown over this URL: <https://yourgithubusername.github.io/categories/>

## RSS

The generated [RSS feed](https://en.wikipedia.org/wiki/RSS) of your blog can be found at <https://yourgithubusername.github.io/feed>. You can see the example RSS feed over [here](https://www.amitmerchant.com/reverie/feed).

## Sitemap

The generated sitemap of your blog can be found at <https://yourgithubusername.github.io/sitemap>. You can see the example sitemap feed over [here](https://www.amitmerchant.com/reverie/sitemap).
