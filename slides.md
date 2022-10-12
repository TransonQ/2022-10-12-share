---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS
css: unocss
---

# 分享顺便测试

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    开始 <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---

# 最近值得关注的大事件

- [axios v1.1.0 版本大事件](https://www.oschina.net/news/212815/axios-pushed-a-broken-update-crippling)

```html
<script src="https://unpkg.com/axios@1.1.0/dist/axios.min.js"></script>
<script>
  axios.get(...)
</script>
```

> 有开发者认为，受此问题影响的开发者在某种程度上 “不值得同情”，因为他们的生产应用在 CDN 上使用了最新（自动升级）的版本库，这是十分愚蠢的行为。

---

# 分享本次的 markdown->网页 ppt 的库

## [slidev](https://cn.sli.dev/)

- markdown 语法
- unocss 还可以 windcss (比较成功的还是 tailwindcss)
- 组件化用的 vue 语法
- 这个作者 开源大佬 [antfu](https://github.com/antfu)

​ <img src="https://github.com/antfu.png" class=" h-40 rounded shadow"  />

---

# 浏览器新标签页

## [itab](https://itab.link/)

![image-20221012105323533](/image-20221012105323533.png)

---

# 上次分享的 valtio

## [被选加进了国内著名的元框架 Umi](https://umijs.org/docs/max/valtio)

<br/>

- 小小整理了一下
- [notion 文档链接](https://quanscheng.notion.site/Valtio-Umi-06e76ce2dc734d268a01e00901a126c6)
