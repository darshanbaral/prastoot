+++
title = "Code Content"
template = "code-content"
next = "tableExample"
+++

```html
{{ define "main" }}
<div class="row no-gutters">
  <div class="col-sm-4 order-sm-2">
    {{ partial "profilePhoto" . }}
    {{ partial "aboutDesc" . }}
    <hr style="width:50%;" />
    {{ partial "language.html" . }}
    <hr style="width:50%;" />
    {{ partial "hobby.html" . }}
  </div>

  <div class="col-sm-8 text-white p-2">
    {{ partial "experience.html" . }}
    {{ partial "education.html" . }}
    {{ partial "project.html" . }}
    {{ partial "skill.html" . }}
  </div>
</div>
{{ end }}
```

|||

## Lorem Ipsum

What is this life if full of care?
