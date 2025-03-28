# commonux
Another Git Space about UX Ethics

## Stack Setup

**Frontend (Next.js):**

- Static generation or SSR (your call)
- TailwindCSS for styling
- Markdown or CMS integration for articles

**Backend Options:**
Since FTP deployment typically means no server logic (unless you're using VPS or similar), you can go with:

1. **Static Markdown + Static Site Generator (SSG)** → Easiest FTP-compatible solution.
2. **Headless CMS with API** (e.g., [Strapi](https://strapi.io/), [Sanity](https://www.sanity.io/), [Contentful](https://www.contentful.com/)) if you host the CMS elsewhere.
3. **Flat-file CMS** like [Netlify CMS](https://www.netlifycms.org/) or [KeystoneJS](https://keystonejs.com/) (requires Node runtime).
