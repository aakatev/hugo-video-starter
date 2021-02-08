---
title: 'Usage Example'
date: 2020-09-20T19:02:50-07:00
description: 'Learn more about the usage and customization.'
draft: false
---

Out of the box, Hugo has support for Youtube and Vimeo, but lacks the support for the media coming from any other resources. This is a starter for using [Hugo](https://gohugo.io/) with various media files from various resources. It is using [Clappr](https://github.com/clappr/clappr).

Clappr is an extensible media player for the web. Your architecture is projected primarily into plugins, adding low accoupling by design to the project and the possibility to add infinitely features easily.

{{< video "http://qthttp.apple.com.edgesuite.net/1010qwoeiuryfg/sl.m3u8" "d-flex justify-content-center my-5" >}}

### Insallation

1. Clone the repo:

```bash
git clone https://github.com/aakatev/hugo-video-starter.git
```

2. Install dependencies:

```bash
npm i
```

3. Start developing:

```bash
npm start
```

For the other available scripts refer to the `package.json`, or [Victor Hugo](https://github.com/netlify-templates/victor-hugo) repository.

### Usage in MD File

The player element can be added to your markdown, like so:

```md

### This is some MD file

{{</* video "http://example.com/video" "my-class-name" */>}}
```

The player element is created using Hugo [shorthands](https://gohugo.io/content-management/shortcodes).

---

### Enjoy!! 😸
