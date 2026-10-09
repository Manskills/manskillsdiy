# Manskills DIY

Source for **Manskills DIY**, a step-by-step how-to blog covering car maintenance,
home repair, and small mechanical fixes. Built with [Jekyll](https://jekyllrb.com/)
and hosted on GitHub Pages (theme: minima).

Currently served at <https://manskills.github.io/manskillsdiy/>. When the custom
domain `manskillsdiy.com` is set up, change `baseurl` in `_config.yml` to `""`.

## Structure

```
_config.yml               Site settings (title, theme, baseurl, plugins, permalinks)
Gemfile                   github-pages gem for local builds
index.md                  Home page (intro + latest guides)
about.md                  About page
affiliate-disclosure.md   FTC-style affiliate disclosure
_posts/                   Published guides (YYYY-MM-DD-slug.md)
_drafts/                  Unpublished guides (slug.md, no date), not built on Pages
assets/images/            Images for posts
```

Categories (set in each post's front matter):

- `car-maintenance`
- `home-repair`
- `small-fixes`

Permalinks follow `/:categories/:title/`, e.g. `/car-maintenance/how-to-change-oil-1991-toyota-corolla/`.

## Adding a post

1. Create `_drafts/your-slug.md` with front matter:

   ```yaml
   ---
   title: "How to ..."
   description: "One-sentence summary for search results."
   categories: [car-maintenance]   # or home-repair / small-fixes
   tags: [tag-one, tag-two]
   needs_fact_check: true
   ---
   ```

2. Write it: tools/materials list, safety notes, numbered steps.
3. Any spec you haven't confirmed (capacities, torque, part numbers, sizes) gets a
   **[VERIFY: ...]** marker. Put sources for confirmed specs in an HTML comment.
4. Affiliate links use `AFFILIATE_LINK_PLACEHOLDER` until accounts exist, and
   every post with affiliate links includes a disclosure line.
5. When every `[VERIFY: ...]` is resolved, set `needs_fact_check: false` and move
   the file to `_posts/YYYY-MM-DD-your-slug.md` to publish.

## Local preview (optional)

```
bundle install
bundle exec jekyll serve --drafts
```
