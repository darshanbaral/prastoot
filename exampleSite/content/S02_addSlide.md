+++
title = "*Adding Slides*"
template = "content-content"
next = "S03_slideTemplates"
+++

## Title Slide

Provide the information of title slide in the `config.toml`.

```toml
[params]
date = "2021-03-18"
author = "Darshan Baral"
  [params.titleSlide]
  title = "**Prastoot**"
  subtitle = "Making presentations using `hugo`"
  next = "S01_about"
```

The filename of the first slide after the title slide is specified in the `next` field without the extension `.md`.

|||

## Additional Slides

Create a separate markdown file for each slide. Relevant slide information should be included in the frontmatter. The frontmatter of all slides except the last one should have the filename (without the extension `.md`) of the follwing slide in `next` field.

```toml
title = "Image Template"
template = "image"
image = "images/apple.jpg"
caption = "Granny Smith Apple"
next = "iframeExample"
```