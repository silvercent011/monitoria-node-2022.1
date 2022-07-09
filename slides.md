---
theme: apple-basic
layout: intro-image
image: "./images/infinite.jpg"
fonts:
  # basically the text
  sans: "Fira Sans"
  # use with `font-serif` css class from windicss
  serif: "Robot Slab"
  # for code blocks, inline code, etc.
  mono: "Fira Code"
---

<div class="absolute top-10 text-shadow-xl">
  <span class="font-700">
    Engenharia de Software - 2022.1
  </span>
</div>

<div class="absolute bottom-10 text-shadow-xl">
  <h1><logos-nodejs-icon/> Node.js + Express</h1>
  <h2>Enquanto você lê este subtítulo, um novo framework JavaScript é criado, e isso é culpa do Node!</h2>
  <h3>
    Vue >>> React
  </h3>
</div>

---

<div class="flex flex-col h-full">
<div class="flex">
<div class="flex flex-1 m-2 flex-col h-auto bg-slate-700 p-5 rounded-lg">
  <img class="rounded-full w-40 mx-auto" src="https://avatars.githubusercontent.com/u/38598808?v=4"/>
  <div class="p-5">
    <h1>Sidney Alex</h1>
    <h2> <logos-google-gmail /> saaa@cin.ufpe.br</h2>
    <h2> <logos-github-icon  /> @silvercent011</h2>
    <h2> <logos-discord-icon /> S1d3A</h2>
  </div>
</div>
<div class="flex flex-1 m-2 flex-col h-auto bg-slate-700 p-5 rounded-lg">
  <img class="rounded-full w-40 mx-auto" src="https://avatars.githubusercontent.com/u/50752448?v=4"/>
  <div class="p-5">
    <h1>André Filho</h1>
    <h2> <logos-google-gmail /> acasfd@cin.ufpe.br</h2>
    <h2> <logos-github-icon  /> @mrdedede</h2>
  </div>
</div>
</div>
<div>
<h1>Nos apresentando</h1>
<h2>(eh o crime, eh nois)</h2>
</div>
</div>
---
layout: image
image: './images/node_bg.jpg'
---

# Como chegamos ao Node?

---

# O contexto das webs

<div class="h-50">
  <img class="h-100 mx-auto" src="/images/webs.jpg"/>
</div>

---

<div class="h-100">
  <img class="h-full mx-auto" src="/images/mosaic.jpeg"/>
</div>

---

<div class="h-100">
  <img class="h-full mx-auto" src="/images/netscape.png"/>
</div>

---

# Schema (Paradigma funcional)

<div class="flex items-center">
<div class="flex">
  <img class="h-50  w-50 mx-auto" src="/images/scheme.png"/>
</div>
<div class="flex-1">

```js
//Scheme Code
(import
    (rnrs)
    (ironscheme clr))

//Define a function write-ln
(define (write-ln fmt . args)
    (clr-static-call System.Console WriteLine
    (clr-cast System.String fmt)
    (clr-cast System.Object[]
    (list->vector args))))

//And invoke it!
(write-ln "{0}" "Hello World!")
```
</div>
</div>

<style>
#slide-content {
  margin: 0px;
  padding:0px;
  display: "flex";
  flex-direction: "row";
  min-height: "100vh";
  align-items: "center";
}
</style>

---
layout: image
image: './images/java-doom-hells-gate.jpg'
---

# Java - (Sintaxe)

---