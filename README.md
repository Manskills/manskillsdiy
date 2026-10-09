# Manskills DIY

Source for **Manskills DIY**, a step-by-step how-to blog covering car maintenance,
home repair, and small mechanical fixes. Built with [Jekyll](https://jekyllrb.com/)
on GitHub Pages using the minima theme (with local overrides).

Live at <https://manskills.github.io/manskillsdiy/>. When the custom domain
`manskillsdiy.com` is set up, change `baseurl` in `_config.yml` to `""`.

## Structure

```
_config.yml               Site settings (theme, baseurl, plugins, affiliates flags, layout defaults)
_data/navigation.yml      Header menu
_data/categories.yml      Categories (slug, title, icon, blurb) used by cards, breadcrumbs, category pages
_data/authors.yml         Author/byline profiles
_layouts/home.html        Home: hero, category cards, featured guide, latest guides, trust strip
_layouts/howto.html       How-to post layout (driven by front matter)
_layouts/category.html    Category landing pages
_includes/                Header/footer overrides + how-to components (specs table, tools list,
                          product box, paid-link helper, FAQ, sources, author box, ...)
assets/main.scss          minima variable overrides + component styles
car-maintenance/, home-repair/, small-fixes/   Category landing pages
index.md, about.md, how-we-research.md, affiliate-disclosure.md
_posts/                   Published guides (YYYY-MM-DD-slug.md)
_drafts/                  Unpublished guides (slug.md), not built on Pages
_templates/howto-post.md  Front-matter template for new guides (excluded from the build)
assets/images/            Images for posts
```

Categories: `car-maintenance`, `home-repair`, `small-fixes`. Permalinks follow
`/:categories/:title/`.

## Adding a guide

1. Copy `_templates/howto-post.md` to `_drafts/your-slug.md` and fill in the front matter
   (specs, tools, materials, safety, faq, sources) and the steps.
2. Every spec gets `status: verify` until it's confirmed against a cited source; the
   page shows a "Not yet verified" badge for those rows.
3. Affiliate URLs stay `AFFILIATE_LINK_PLACEHOLDER` until accounts exist. Placeholders
   render as plain text / "Link coming soon", never as links. Inline paid links use
   `{% include aff-link.html text="..." url="..." retailer="Amazon" %}`.
4. When every spec is verified, set `needs_fact_check: false` and move the file to
   `_posts/YYYY-MM-DD-your-slug.md`.

## Affiliate settings

`_config.yml` → `affiliates.amazon_enrolled` stays `false` until the Amazon Associates
account is approved. Setting it to `true` shows the required statement
"As an Amazon Associate I earn from qualifying purchases."

## Local preview (optional)

```
bundle install
bundle exec jekyll serve --drafts
```
