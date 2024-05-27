---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides, markdown enabled
title: Software Test
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply any unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
---

# Software Test

Presentation slides for developers

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---

#  What is Software Testing?

<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;软件测试就是确保软件或者应用程序正常运行的过程，测试方法种类繁多，方法不同需求也不同。

例如，单元测试需要编写测试用例验证代码是否存在缺陷；β测试需要回测历史版本确保既有功能的正常使用。

软件测试是软件开发生命周期的重要组成部分，协助提升开发效率和产品性能，打造符合要求的优质产品。

此外，测试还能降低缺陷率，降低开发成本投入，缩短开发时间。

<!-- - 📝 **Text-based** - focus on the content with Markdown, and then style them later
- 🎨 **Themable** - theme can be shared and used with npm packages
- 🧑‍💻 **Developer Friendly** - code highlighting, live coding with autocompletion
- 🤹 **Interactive** - embedding Vue components to enhance your expressions
- 🎥  **Recording** - built-in recording and camera view
- 📤**Portable** - export into PDF, PPTX, PNGs, or even a hostable SPA
- 🛠 **Hackable** - anything possible on a webpage -->

<br>

Read more about [What is Software Testing?](https://www.freecodecamp.org/news/software-testing-beginners-guide/)

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
transition: slide-up
level: 2
---

# Classification

## 功能测试
功能测试是验证系统是否按照客户需求或者规范运行。

这类测试旨在验证每个功能正确输入后会有对应的正确输出。

例如，编写一条测试创建用户的测试用例，用例中包含邮箱地址、姓名和密码等格式正确的输入内容，验证成功创建用户。

功能测试就是根据功能需求，模拟业务场景，验证功能的正常使用。
## 非功能测试
非功能测试是验证终端用户的使用体验，如压力测试下的性能表现与稳定性，这对用户体验至关重要。

用户可能无法直观感知到非功能测试发现的代码问题，但也是系统中的重点问题。

非功能测试就是测试加压后软件会如何响应。

---
layout: two-cols
layoutClass: gap-16
---

# 功能测试

## 单元测试
<br/>

## 集成测试
<br/>

## 系统测试
<br/>

## 验收测试
<br/>

## 回归测试
<br/>

## α测试与β测试<br/>


---
level: 2
---

# 测试和测试开发工程师
<br/>

## 测试工程师
<br/>

### 测试工程师主要专注于手动测试，包括执行测试案例、报告软件中的bug、确保产品质量符合预期。
<br/>

## 测试开发工程师
<br/>

### 软件测试开发工程师在进行测试的同时，还涉及到测试工具和框架的开发，他们不仅要发现错误，还要通过自动化测试提高测试的效率和覆盖率。

---
class: px-20
---

# 软件测试公司(OD)
### 文思海辉
<br/>

### 中软国际
<br/>

### 法本信息
<br/>

### 德科信息
<br/>

### 亚信联创
<br/>

### 东软集团
<br/>

### 浪潮集团
<br/>

### 微创软件
<br/>

---
class: px-20
---

# 软件测试的就业方向
<br/>

手机APP测试：手机APP分为android和ios个平台，平台不同，功能、兼容性、自动化框架不同，这几年移动互联网的爆发式发展让手机APP测试工程师需求大量增加。

Web测试：在几年之前，移动端互联网没有爆发之前，Web测试是测试的主流方向，虽然现在被移动互联网分了一杯羹，但是需求仍然很大，Web测试包括网站测试，Web服务器测试。

游戏测试：只要有游戏就有游戏测试，手游和网游都需要，如果你喜欢玩游戏，从事游戏测试再适合不过了。

网络设备测试：这块测试一般工程量比较大，服务的都是企业级的客户，比如路由器、防火墙，像华为、中兴、电信等企业每年都需要大量的网络设备测试工程师。

金融测试：金融业软件测试作为整个金融产品生产周期中重要的一个环节，起着重要作用，尤其是对金融产品创新和风险控制等方面有着不可或缺的作用。金融测试同时也需要一定的业务能力和金融知识。

云产品测试：这是现在较新的测试领域，还处于初级发展阶段，主要是领域是云存储和云计算。比如说阿里云，百度云，我国现在的在大力发展云产品，做云产品测试是一个不错的发展方向。

---
layout: center
class: text-center
---

# Thanks
