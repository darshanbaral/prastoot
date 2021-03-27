+++
title = "Slide Templates"
template = "content-content"
next = "codeExample"
+++

## Available Templates

1. `content`: for generic content - accepts markdown.
2. `code`: for standalone code snippets - accepts markdown.
3. `image`: for images. `src` field is required in the frontmatter and the `caption` field is optional.
4. `iframe`: for embedding webpages or youtube videos. `src` field is required in the frontmatter.
5. `table`: for single tables. `caption` field in the frontmatter is optional.

`template` should be specified in the frontmatter of the markdown file.

|||

## Combining Templates

Up to two templates can be combined. If only one template is used, the whole width is taken up by it. If two templates are used, then each will take half the width.

For example, `template = "content-code"` will render generic content on the left side and code snippets on the right side.

To render combinations of two codes, two genereic contents, or a generic content and a code, use separator <code>|</code><code>|</code><code>|</code> (three vertical bars) in the markdown file.