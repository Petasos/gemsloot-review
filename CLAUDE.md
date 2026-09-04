# CLAUDE.md

## Preview URLs

This repo is a static HTML site (`index.html` + `assets/`, no build step). GitHub Pages
serves only the `main` branch (see `CNAME`: gemsloot.win), so other branches and commits
need an alternate way to preview.

When Bart asks for "een preview URL" / "a preview URL" for a branch or commit in this
project, generate an htmlpreview.github.io URL wrapping the raw GitHub content, in this
exact format:

```
https://htmlpreview.github.io/?https://raw.githubusercontent.com/Petasos/gemsloot-review/<branch-or-commit>/index.html
```

Default to the current branch (or the commit just discussed) unless he names a different
one. Just produce the URL — don't ask him to re-explain what he means.
