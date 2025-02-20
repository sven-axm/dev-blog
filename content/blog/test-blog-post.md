---
author: Sven Axmann
title: First post
date: 2022-10-01
description: This is my first blog post.
tags: ["blog"]
thumbnail:
  url: img/notepad.jpg
  author: Frederick Medina
  authorURL: https://unsplash.com/@frederickjmedina
  origin: Unsplash
  originURL: https://unsplash.com/photos/PdfRE-xB--s
includeToc: true
draft: true
---


# Abbr
{{< abbr HTML >}}
{{< abbr key="html" class="initialism" >}}

# Accordion
{{< accordion id="accordion-default" >}}
  {{< accordion-item header="Accordion Item #1" show="true" >}}
    This is the first item's accordion body. It supports Markdown content. The item is shown by
    adding the value `show` to the `class` argument.
  {{< /accordion-item >}}
  {{< accordion-item header="Accordion Item #2" >}}
    This is the second item's accordion body. It too supports Markdown content.
  {{< /accordion-item >}}
  {{< accordion-item header="Accordion Item #3" >}}
    This is the third item's accordion body.
  {{< /accordion-item >}}
{{< /accordion >}}

# Alert
{{< alert color="danger" >}}
    A simple danger alert—check it out!
{{< /alert >}}

# Animation
<!-- {{< animation data="animation/gatin.json" auto=false hover=true class="col-6 mx-auto" >}} -->

# Badge
Example heading of size four {{< badge title="New" >}}
{.h4}

# Blockquotes
> Tiam, ad mint andaepu dandae nostion secatur sequo quae.
> **Note** that you can use _Markdown syntax_ within a blockquote.

> Don't communicate by sharing memory, share memory by communicating.
>
> — _Rob Pike[^1]_
[^1]: The above quote is excerpted from Rob Pike's [talk](https://www.youtube.com/watch?v=PAAkCSZUG1c) during Gopherfest, November 18, 2015.

# Breadcrumb
{{< breadcrumb path="first-blog-post" >}}

# Card
{{< card path="/blog/first-blog-post-copy" header="publication" footer="tags" orientation="horizontal" class="col-sm-12 col-lg-8 mx-auto" />}}

# Card Group
{{< card-group padding="3" gutter="3" >}}
    {{< card title="Bootstrap framework" icon="fab bootstrap" >}}
        Build fast, responsive sites with Bootstrap 5. Easily customize your site with the
        source Sass files.
    {{< /card >}}
    {{< card title="Full text search" icon="fas magnifying-glass" >}}
        Search your site with FlexSearch, a full-text search library with zero dependencies.
    {{< /card >}}
    {{< card title="Development tools" icon="fas code" >}}
        Use Node Package Manager to automate the build process and to keep track of
        dependencies.
    {{< /card >}}
{{< /card-group >}}

# Carousel
{{< carousel ratio="16x9" class="col-sm-12 col-lg-8 mx-auto" >}}
  {{< img src="img/me.jpg" caption="slide 1" >}}
  {{< img src="img/me.jpg" caption="slide 2" >}}
  {{< img src="img/me.jpg" caption="slide 3" >}}
{{< /carousel >}}

# Codeblock
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Example HTML5 Document</title>
  </head>
  <body>
    <p>Test</p>
  </body>
</html>
```

# Collapse
{{< button collapse="collapse-1" >}}
    Trigger panel
{{< /button >}}

{{< collapse id="collapse-1" class="p-3 border rounded" >}}
    Some placeholder content for the collapse component. This panel is *hidden by default* but
    revealed when the user activates the relevant trigger.
{{< /collapse >}}

# Command Prompt
{{< command >}}
export MY_VAR=123
{{< /command >}}

# Github-style Alerts
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

# Icon
{{< icon fa square-check >}}
{{< fa square-check >}}
{{< fab linkedin >}}
{{< fas circle-check >}}
<!-- {{< icon custom activity >}} -->

# Image
{{< image src="img/me.jpg" caption="Image caption" >}}

# Underline Text
This is an {{< ins >}}underlined text{{< /ins >}}.

# Kbd
{{< kbd title="primary" color="primary" >}}
{{< kbd title="secondary" color="secondary" >}}
{{< kbd title="success" color="success" >}}
{{< kbd title="danger" color="danger" >}}
{{< kbd title="warning" color="warning" >}}
{{< kbd title="info" color="info" >}}
{{< kbd title="light" color="light" >}}
{{< kbd title="dark" color="dark" >}}

# Links
<!-- {{< link mozilla_image />}} -->

# Math
This is an inline $-b \pm \sqrt{b^2 - 4ac} \over 2a$ formula
This is not an inline formula:
$$x = a_0 + \frac{1}{a_1 + \frac{1}{a_2 + \frac{1}{a_3 + a_4}}}$$
$$\forall x \in X, \quad \exists y \leq \epsilon$$

```math
-b \pm \sqrt{b^2 - 4ac} \over 2a
```

# Tabs
{{< nav id="links-1" fade="true" >}}
  {{< nav-item header="Nav Item #1" show="true" >}}
    This is the first item's nav body. It supports Markdown content. The item is shown by adding
    the value `show` to the `class` argument.
  {{< /nav-item >}}
  {{< nav-item header="Nav Item #2" >}}
    This is the second item's nav body.
  {{< /nav-item >}}
  {{< nav-item header="Nav Item #3" disabled="true" />}}
{{< /nav >}}


# Table
{{< table >}}
| #  | Heading | Heading | Heading | Heading | Heading | Heading | Heading | Heading | Heading |
|----|---------|---------|---------|---------|---------|---------|---------|---------|---------|
| 1. | cell    | cel     | cel     | cel     | cel     | cel     | cel     | cel     | cel     |
| 2. | cell    | cel     | cel     | cel     | cel     | cel     | cel     | cel     | cel     |
| 3. | cell    | cel     | cel     | cel     | cel     | cel     | cel     | cel     | cel     |
{{< /table >}}


# Timeline

# Tooltip
{{< tooltip color="info" title="Tooltip" href="#!" >}}
    Tooltip demonstration
{{< /tooltip >}}

# Video
{{< youtube w7Ft2ymGmfc >}}


