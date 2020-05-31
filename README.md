# zola-jtd-demo
Demo Site using Zola Just the Docs

# Installing the theme

```bash
git remote add zola-jtd git@github.com:jakeswenson/zola-just-the-docs.git
git subtree add --prefix themes/just-the-docs zola-jtd master
```

# Pulling in `google/engineering-practices` content

> https://stackoverflow.com/a/30386041/24730

```bash
git read-tree --prefix=content/reviews -u google-eng/master:review/
```
