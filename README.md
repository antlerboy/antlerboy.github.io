# Book of Questions crawler policy

This small repository serves https://antlerboy.github.io/robots.txt through GitHub Pages, using the main branch and repository root.

The policy excludes only `/book-of-questions/` and the exact slashless `/book-of-questions` URL. All other project paths are unaffected. The website itself remains in the separate `antlerboy/book-of-questions` repository and stays publicly accessible without sign-in.

The wildcard group covers compliant crawlers; the second group explicitly names major AI/search/training crawlers. Do not replace the path-specific exclusions with `Disallow: /`, as that would affect unrelated projects on the hostname.

Robots rules are voluntary, not authentication or a technical guarantee against scraping, indexing or AI training. They do not govern public GitHub source, raw files, APIs or clones. No content licence is granted by these rules.

The `.nojekyll` file keeps this policy as plain static content. No home page or redirects are added.
