---
# GENERAL
theme: default
author: Thomas PIERRE for StudioB04
titleTemplate: '%s | StudioB04'
title: StudioB04
keywords: Formation, Svelte, Web, Javascript
favicon: favicon.png
colorSchema: light
contextMenu: false
htmlAttrs:
  dir: ltr  
  lang: fr

# STYLE
fonts:
  sans: Red Hat Display
  serif: Robot Slab
  mono: monospace
themeConfig:
  primary: var(--primary-500)
  secondary: var(--secondary-500)

# CONFIG
presenter: true
lineNumbers: true
monaco: true
monacoTypesSource: local
selectable: true
drawings:
  enabled: true
  persist: false
  presenterOnly: true
  syncAll: true
mdc: true

layout: cover # https://sli.dev/builtin/layouts
transition: fade-out
src: ./slides/accueil.html
---

--- 
title: Programme
src: ./slides/programme.html
---

--- 
title: Présentation de Svelte
src: ./slides/presentation.html
---

--- 
title: La syntaxe de Svelte
src: ./slides/syntaxe.html
---

--- 
title: Les conditions
src: ./slides/conditions.html
---

--- 
title: Les boucles
src: ./slides/boucles.html
---

--- 
title: Les évènements
src: ./slides/evenements.html
---

--- 
title: la réactivité
src: ./slides/reactivite.html
---

--- 
title: le binding
src: ./slides/binding.html
---

--- 
title: Passons à la pratique
src: ./slides/TP.html
---