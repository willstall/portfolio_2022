---
title: "Demo"
subtitle: "Creative Engineer"
description: ""
# weight: 4
date: 2022-08-19T13:33:40-04:00
menu: "main"
draft: true
---

# We're just gonna **try out some shit** and ~~hope~~ it all works

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

A NAUGHTY First Level Header
====================

A SEXY Second Level Header
---------------------

## Highlight
{{< highlight html >}}
<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Pages }}
        {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
{{< /highlight >}}

<!-- ### Alt Title -->
<!-- ![alt text](/about/cp-logo.png "Title") -->
<!-- {{< figure src="/about/cp-logo.png" title="Cipher Prime Logo" class="cover">}} -->

## Inline Image
{{< imgs/inline "/about/cp-logo.png" >}}

## Full Image
{{< imgs/full "/about/cp-logo.png" >}}

## Cover Image


[^1]: This is the footnote.
[^2]: This is the footnote.
### Footnotes
Here's a sentence with a footnote. [^1]
Here's a sentence with *yet another footnote*. [^2]

### Blockqoute
> If you want to stay up to date on my art, I post here on [Instagram](http://instagram.com/willstall)

### Fenced Code

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Goat
[Documentation Here](https://github.com/bep/goat)
```goat
      .               .                .               .--- 1          .-- 1     / 1
     / \              |                |           .---+            .-+         +
    /   \         .---+---.         .--+--.        |   '--- 2      |   '-- 2   / \ 2
   +     +        |       |        |       |    ---+            ---+          +
  / \   / \     .-+-.   .-+-.     .+.     .+.      |   .--- 3      |   .-- 3   \ / 3
 /   \ /   \    |   |   |   |    |   |   |   |     '---+            '-+         +
 1   2 3   4    1   2   3   4    1   2   3   4         '--- 4          '-- 4     \ 4

```

### Table
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |



