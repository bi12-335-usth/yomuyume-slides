---
transition: slide-left
class: -top-5
title: Introduction
---

<img src="/assets/yomuyume.png" width="100px">

# Yomuyume
## A self-hosted manga/comic media server
## with advanced recommendation system

---

# Table of contents

<Toc minDepth="1" maxDepth="1" />

---
layout: image-right
image: /assets/current-solutions.png
title: Problems and Goals
---

# Problems
we have with current solutions

- Bad UI/UX design choices
- Too slow, too much performance overhead
- No longer maintained
- Inconvenient to manage metadata
- Have primitive/no recommendation system

*and more...*

# Goals

- Resolving the problems above
- Trying out new technologies
- Experimenting with machine learning

---
layout: image-right
image: /assets/home.png
---

# Highlights
Yomuyume is a platform that allows you to

- Own your data - bring your own library
- Share it with friends or the internet
- Track reading progress
- Get recommendations based on your preferences

Built with fast and modern technologies

<NuxtRust />

---

# Tech stack decisions

## Nuxt.js
- Built on top of Vue.js
- Faster, more ergonomic than React
- Single-File Components

```vue {all|1-3|5-7|9-14|all}
<script setup lang="ts">
const greeting: Ref<string> = ref('Hello World!')
</script>

<template>
  <p class="greeting">{{ greeting }}</p>
</template>

<style>
.greeting {
    color: red;
  font-weight: bold;
}
</style>
```

---

## Rust

- Neck-to-neck with C/C++ in performance
- Has one of the best tooling and ecosystems
- The compiler is a friend

```bash
$ cargo run
   Compiling patterns v0.1.0 (file:///projects/patterns)
error[E0308]: mismatched types
 --> src/main.rs:2:9
  |
2 |     let (x, y) = (1, 2, 3);
  |         ^^^^^^   --------- this expression has type `({integer}, {integer}, {integer})`
  |         |
  |         expected a tuple with 3 elements, found one with 2 elements
  |
  = note: expected tuple `({integer}, {integer}, {integer})`
             found tuple `(_, _)`

For more information about this error, try `rustc --explain E0308`.
error: could not compile `patterns` due to previous error
```
