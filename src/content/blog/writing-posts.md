---
title: 'How this blog works'
description: 'Where posts live, how they publish, and what to edit.'
pubDate: 'Aug 18 2026'
---

Posts are content collections in Astro. Add a `.md` or `.mdx` file under `src/content/blog/`, commit, and push to `main`. GitHub Actions builds the site and publishes it to Pages.

Optional hero images go in `src/assets/` and get referenced from frontmatter:

```md
---
title: 'A longer piece'
description: 'What this post is about'
pubDate: 'Sep 01 2026'
heroImage: '../../assets/blog-placeholder-1.jpg'
---
```

Edit site-wide copy in `src/consts.ts` (title, description, social links, project list). The homepage is `src/pages/index.astro`.
