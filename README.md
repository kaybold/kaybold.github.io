# KayBold Website

## How to Publish Blog Posts

### Adding a new post as a draft (hidden)

When you add a new post to `blog.html` but aren't ready to show it yet, add the word `draft` to the class:

```html
<a class="pub-item draft" href="insights/my-new-post.html">
  <h3 class="pub-item__title">My New Post Title</h3>
  <p class="pub-item__meta">February 2026</p>
  <p class="pub-item__desc">A short description of the post.</p>
</a>
```

The post won't appear on the site until you publish it.

### Publishing a post

When you're ready to publish, just remove the word `draft`:

```html
<a class="pub-item" href="insights/my-new-post.html">
```

That's it!

### Remember

- New posts go at the **top** of the Insights section (newest first)
- The homepage automatically shows the most recent published post
