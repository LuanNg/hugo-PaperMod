---
title: "How to Write a Complete Blog Post on Hugo CMS"
date: 2026-01-01T09:00:00+07:00
summary: "A step-by-step guide to writing and publishing a professional blog post using Hugo CMS."
tags: [hugo, tutorial, blogging]
---

Writing a complete, professional blog post on Hugo CMS is simple and powerful. Here’s how you can do it:

## 1. Create a New Post

Run the following command in your project directory:

```sh
hugo new posts/my-first-post.md
```

## 2. Edit the Markdown File

Open the new file in `content/posts/` and add your content. Use front matter for metadata:

```markdown
---
title: "My First Post"
date: 2026-01-01T09:00:00+07:00
draft: false
summary: "A short summary of my post."
tags: [python, ai]
---

Your post content goes here. You can use Markdown for formatting, code blocks, images, and more.
```

## 3. Add Images and Code

- Place images in the `assets/images/` folder and reference them in your post.
- Use triple backticks for code blocks:

```python
print("Hello, Hugo!")
```

## 4. Preview Your Post

Start the Hugo server:

```sh
hugo server
```

Visit `http://localhost:1313` to preview your post.

## 5. Publish

Set `draft: false` in the front matter to publish your post. Commit and deploy your site as usual.

---

For more tips, see the [official Hugo documentation](https://gohugo.io/getting-started/).
