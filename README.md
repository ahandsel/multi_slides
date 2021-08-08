[Use reveal-md to generate multiple slides and host them on GitHub Page - Hank Learning](https://blog.hanklu.tw/post/2021/use-reveal-md-to-generate-multiple-slides-and-host-them-on-github-page/)

## reveal-md

Install

```zsh
npm install -g reveal-md
```

Start local server with auto reload option

```zsh
reveal-md path/to/my/slides.md -w
```

## package.json

```json
    "start": "reveal-md content/ -w",
    "build": "rm -rf docs && reveal-md content/ --static docs --static-dirs=content/attachments &&mv docs/_assets docs/assets"
```

## Themes

  - beige
  - black
  - blood
  - league
  - moon
  - night
  - serif
  - simple
  - sky
  - solarized
