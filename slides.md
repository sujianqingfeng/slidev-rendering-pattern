---
layout: cover
highlighter: shiki
colorSchema: dark
transition: fade-out
title: Rendering Pattern
mdc: true
---

<h1 flex="~ col">
  <div text-2xl op50>Web</div>
  <div>Rendering Pattern<span opacity-50 text-4>(渲染模式)</span></div>
</h1>


---
layout: center
growX: 50
growY: 50
---

# 什么是渲染模式

<div text-center text-4 v-click>
  如何将数据呈现给用户的一种模式
</div>



---
layout: center
growX: 50
growY: 50
---

# 为社么我们需要渲染模式 



---
layout: cover
growX: 0
growY: 50
---

<div/>


<div leading-20 text-8 ml-20>

  <v-clicks>

  - 开发体验（DX）
  - 用户体验（UX）
  </v-clicks>
</div>



---
layout: center
growX: 50
growY: 50
---

# 如何衡量用户体验


---
class: h-full
clicks: 2
--- 

<h1>Web Vitals</h1>



<div class="h-80" flex="~ justify-around items-center">
 <div p-2 text-center border-rounded-2 :border="$clicks >= 1 ? '1px dashed green':'1px transparent'">
    <div text-10>LCP</div>
    <div>Largest Contentful Paint</div>
 </div>

 <div p-2 text-center border-rounded-2 :border="$clicks === 2 ? '1px dashed green':'1px transparent'">
    <div text-10>FID</div>
    <div>First Input Delay</div>
 </div>

 <div text-center>
    <div text-10>CLS</div>
    <div>Cumulative Layout Shift</div>
 </div>
</div>



<!-- 
渲染模式跟前面两个有关 我们关注前两个
-->

---
layout: center
growX: 50
growY: 50
---


<h1>
  有那些渲染模式
</h1>


<v-click>
<div absolute top-75 text-6 left-80>static rendering</div>
<div absolute top-75 text-6 left-128>ssg</div>
<div absolute top-75 text-6 left-145>isg</div>
<div absolute top-75 text-6 left-160 >csr</div>
<div absolute top-85 text-6 left-120>ssr</div>
</v-click>

<v-click>
<div absolute top-50 text-6 left-70>progressive hydration</div>
<div absolute top-50 text-6 left-135>streaming ssr</div>
<div absolute top-40 text-6 left-85>island</div>
<div absolute top-40 text-6 left-108>resumability</div>
<div absolute top-40 text-6 left-148>rsc</div>
</v-click>


---
layout: center
growX: 55
growY: 50
---


# Static Rendering (静态渲染)













---
layout: center
class: text-center
growX: 55
growY: 50
---

# Thank you
Power by [slidev](https://sli.dev) [PPT](https://github.com/sujianqingfeng/slidev-unocss)
