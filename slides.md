---
theme: seriph
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  aarn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
transition: slide-left
title: Capa
mdc: true
presenter: dev
---

# Inteligência Artificial
<div class="w-60 relative mt-6">
  <div class="relative w-40 h-40">
    <img
      v-motion
      :initial="{ scale: 1.2}"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://cdn.openai.com/API/images/guides/image_generation_simple.webp"
    />
 
    
  </div>
</div>
Sidney, Guilherme e Matheus
<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
     <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
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

# Topicos


<Toc maxDepth="1"></Toc>

<br>


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 200%;
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
layout: default
---

# Principais áreas 
- 📝 **Ciência da Computação:** - Bases teóricas e práticas para o desenvolvimento de algoritmos, modelos e técnicas computacionais para simular a inteligência humana.
- 🎨 **Matemática e Estatística** -A matemática e a estatística fornecem os fundamentos teóricos para a modelagem e análise de algoritmos de IA, incluindo aprendizagem de máquina, redes neurais e processamento de dados.
- 🧑‍💻 **Aprendizagem de Máquina** - A aprendizagem de máquina é uma subárea da IA que se concentra no desenvolvimento de algoritmos que permitem aos computadores aprender e melhorar com base em dados

- 🎥 **Neurociência Computacional** A neurociência computacional busca entender o funcionamento do cérebro humano e aplicar esses insights no desenvolvimento de modelos e algoritmos de IA inspirados no cérebro.
- 🛠 **Linguística Computacional** - A linguística computacional envolve o processamento de linguagem natural (PLN), que se concentra no desenvolvimento de algoritmos e técnicas para que os computadores compreendam e processem a linguagem humana.

<br>


---
transition: slide-up
level: 2
---

# Aprendizado de maquina

- 📝 **Linear Regression:** - Bases teóricas e práticas para o desenvolvimento de algoritmos, modelos e técnicas computacionais para simular a inteligência humana.
- 🎨 **Neural Networks** -A matemática e a estatística fornecem os fundamentos teóricos para a modelagem e análise de algoritmos de IA, incluindo aprendizagem de máquina, redes neurais e processamento de dados.
- 🧑‍💻 **XGBoost** - A aprendizagem de máquina é uma subárea da IA que se concentra no desenvolvimento de algoritmos que permitem aos computadores aprender e melhorar com base em dados


---
layout: image-right
---




---

# Rede Neural

<div grid="~ cols-2 gap-4">
<div>

As redes neurais artificiais (RNAs) são modelos computacionais inspirados no sistema nervoso central, especialmente o cérebro, capazes de aprender e reconhecer padrões.
 
Elas são representadas como sistemas de neurônios interconectados que simulam o funcionamento das redes neurais biológicas.

</div>
<div>

```html
<Tweet id="1390115482657726468" />
```

<Tweet id="925014446241734656" scale="0.65" />

</div>
</div>

<!--
Presenter note with **bold**, *italic*, and ~~striked~~ text.

Also, HTML elements are valid:
<div class="flex w-full">
  <span style="flex-grow: 1;">Left content</span>
  <span>Right content</span>
</div>
-->


---
class: px-20
---

# Aprendizado de maquina

- 📝 **Linear Regression:** - Bases teóricas e práticas para o desenvolvimento de algoritmos, modelos e técnicas computacionais para simular a inteligência humana.
- 🎨 **Neural Networks** -A matemática e a estatística fornecem os fundamentos teóricos para a modelagem e análise de algoritmos de IA, incluindo aprendizagem de máquina, redes neurais e processamento de dados.
- 🧑‍💻 **XGBoost** - A aprendizagem de máquina é uma subárea da IA que se concentra no desenvolvimento de algoritmos que permitem aos computadores aprender e melhorar com base em dados

<iframe src="https://giphy.com/embed/YknAouVrcbkiDvWUOR" align="center" width="280" height="150" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/kitp-YknAouVrcbkiDvWUOR">via GIPHY</a></p>


---
preload: false
---

# Chat GPT e API

criar imagens do zero, acresentar algo em uma imagem, criar variações de uma imagem

```py
#Gera imagem
response = openai.Image.create(
  prompt="a white siamese cat",
  n=1,
  size="1024x1024"
)
image_url = response['data'][0]['url']

```

<div class="w-60 relative mt-6">
  <div class="relative w-40 h-40">
    <img
      v-motion
      :initial="{ x: 800, y: -100, scale: 1.5, rotate: -50 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://cdn.openai.com/API/images/guides/image_generation_simple.webp"
    />
 
    
  </div>
</div>

<!-- vue script setup scripts can be directly used in markdown, and will only affects current page -->
<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>

<div
  v-motion
  :initial="{ x:35, y: 40, opacity: 0}"
  :enter="{ y: 0, opacity: 1, transition: { delay: 3500 } }">

[API CHAT GPT](https://platform.openai.com/docs/guides/images/introduction)

</div>

---

# Reconhecimento de gestos



---

# Ciência da Computação visão geral

You can create diagrams / graphs from textual descriptions, directly in your Markdown.

<div class="grid grid-cols-4 gap-5 pt-4 -mb-6">

```mermaid {scale: 0.5}
mindmap
  root((Ciencia da computação))
    inteligência artificial
      aprendizado de máquina
      ::icon(fa fa-book)
        raciocínio automatizado
    algoritimos
      análise de algoritmos
      algoritimos e estrutura de dados
        algoritmos genéticos
    computação cientifica
      bioinformática
    teoria da computação
    	teoria dos automatas
    	teoria da computabilidade
    	teoria da computação complexa
    compiladores e linguagem de programação
    computação grafica
    fundações matematicas
    robótica	 
      
```



</div>

<br>
<br>

[video bom sobre o mapa da ciencia da computação](https://www.youtube.com/watch?v=SzJ46YA_RaA)



---
layout: center
class: text-center
---

# Learn More

[Documentations](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/showcases.html)
