---
transition: slide-left
class: -top-5
title: Introduction
---

<img src="/yomuyume.png" width="100px">

# Yomuyume
## A self-hosted manga/comic media server
## with advanced recommendation system

---

# Table of contents

<Toc minDepth="1" maxDepth="1" />

---
layout: image-right
image: /current-solutions.png
title: Problems and Goals
---

# Problems
we have with current solutions

- Bad UI/UX design choices
- Inconvenient to manage metadata
- No longer maintained
- Too slow, too much performance overhead
- Have primitive/no recommendation system

*and maybe more...*

# Goals

- Resolving the problems above
- Trying out new technologies
- Experimenting with machine learning

<!--
[TODO]
-->

---
layout: center
---

## UI/UX

<!--
First, let's talk about UI/UX

we'll take a look at 2 popular products to better illustrate the problems
-->

---
layout: image
image: /komga-home.png
---

<!--
The first one is Komga

✔️
- 3.1k stars on Github
- The navigation bar is good

❌
- Using material design 2 | released in 2014 - a decade ago
- No artist(s)/author(s) name
- Don't need page cound
-->

---
layout: image
image: /kavita-home.png
---

<!--
And here's Kavita

✔️
- 4.5k stars on Github
- Do like their filtering system (not show here because it's not the main discussion)

❌
- Color palette feels outdated
- No artist(s)/author(s) name
- Don't need to know if it's a manga/comicabcsdajsjal
-->

---
layout: image-right
image: /ymym-home.png
---

## UI/UX

- Put ourselves in the shoes of the readers
- Inspirations from Material Design 3

![](/md3-sample.png)

<!--
To tackle this problem
- We see ourselves as readers, not developers
  - find out which information is important and not
  - how important it is to render them to the readers
- MD3: latest version of Material Design from Google's design team
  - have their Design Kit and Theme Builder on figma
  - -> easy to implement and customize for our own needs
-->

---
layout: center
---

## Performance

<!--
Let's talk about performance
- 2 previous examples
  - Komga uses Kotlin, which runs on JVM
  - Kavita uses C#, which runs on .NET
- Problems both have:
  - garbage collection
  - compile to bytecode, not native code
-->

---
layout: two-cols-header
---

## Performance

::left::

### Nuxt.js

- Built on top of Vue.js
- Faster, more ergonomic than React
- Single-File Components

::right::

### Rust

- Neck-to-neck with C/C++ in performance
- Has one of the best tooling and ecosystems
- The compiler is a friend

<!--
[TODO]
-->

---

## Metadata

<!--
[TODO]
-->

---

[TODO]