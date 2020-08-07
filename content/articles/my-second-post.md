---
title: My second Blog Post
description: Learning how to use @nuxt/content to create a blog
img:
alt: my second blog post
author:
  name: urawa72
  bio: All about urawa72
  img: 'https://s.gravatar.com/avatar/472730f1d40dcf0e225c95200d809130?s=80'
---

<div>
  This is HTML inside markdown that has a class of note.
</div>

<info-box>
  <template #info-box>
    This is a vue component inside markdown using slots
  </template>
</info-box>

<author :author="author" />

