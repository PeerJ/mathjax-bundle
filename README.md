# mathjax-bundle

A Symfony bundle providing MathJax JS files

```
<script src="{{ asset('peerjmathjax/MathJax/MathJax.js') }}"></script>
```

Note: image files are not included, so set `imageFont: null` in your MathJax config.

## Updating

When there is a new MathJax release, run `bower update MathJax` to fetch the latest version of the MathJax files, commit them to this repository and create a new release.
