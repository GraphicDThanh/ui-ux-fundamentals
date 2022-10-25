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

# UX / UI Fundamentals

UX Design Course Tutorial for Beginners

<p>Host by: Thanh Nguyen Diem</p>

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
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

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->
---

# UX vs UI
## UX (User Experience)


- Là: sự tương tác giữa khách hàng và công ty
- Dựa vào: 
  - thiết kế trực quan
  - tâm lý hành vi
  - các nghiên cứu khách hàng
- Áp dụng lên: sản phẩm (trang web, máy bán hàng tự động)

## UI (User Interface)


- Là: 
  - cái nhìn thấy và cảm nhận (look & feel)
  - điểm tương tác giữa người dùng và sản phẩm trên thiết bị kỹ thuật số (touch screen, touch pad)



---
layout: image
image: assets/ui-vs-ux.jpeg
---
<style>
  .slidev-layout.slidev-page-3 {
    background-size: contain !important;
  }
</style>


---
layout: image-right
image: assets/psychology-color.png
---
<style>
  .slidev-layout.slidev-page-4 + div {
    background-size: contain !important;
  }
</style>

---

# Graphic Design
## Psychology of color 
### How does color work?

- Màu sắc ở mọi nơi.
- Chọn đúng màu sẽ giúp người dùng nhận biết thương hiệu
- Mỗi màu sẽ mang đến những cảm xúc khác nhau


---
layout: image-right
image: assets/psychology-color.png
---
<style>
  .slidev-layout.slidev-page-5 + div {
    background-size: contain !important;
  }
</style>

### Understanding color psychology

- não người phản ứng với màu sắc
- khi mắt tiếp xúc với màu sắc, mắt kết nối đến não và gửi tín hiệu tiết ra các loại hóc môn quyết định trạng thái của tâm trạng và cảm xúc
- màu sắc được chọn phù hợp sẽ khiến người dùng phải hành động
- chỉ trong 90s, người dùng sẽ phán xét về một sản phẩm, và từ 62% đến 90% là dựa trên màu sắc


---
layout: image-right
image: assets/psychology-color.png
---
<style>
  .slidev-layout.slidev-page-6 + div {
    background-size: contain !important;
  }
</style>

### Các màu sắc và cảm xúc đặc trưng:

- Red: confidence,  youth, power
- Orange: friendly, warm, energetic
- Yellow: happiness, optimism, warmth
- Green: peace, growth, health
- Blue: trust, security, stability
- Purple: luxurious, creative, wise
- Black: reliable, sophisticated (tinh vi), experienced
- White: simple, calm, clean


---
layout: image-right
image: assets/r-g-b.png
---
### Lý thuyết về màu

RGB: Additive color mixing model

- Red, Green, Blue
- sử dụng: web design, only ads, digital-only files
- mô tả các con người nhận dạng các màu và cách trộn màu, các màu tương phản
- màu sắc được quản lý trong bánh xe màu và chia làm 3 categories: primary colors, secondary colors, tertiary colors

---
layout: image-right
image: assets/cmyk.png
---
CMYK: Subtractive color mixing model

- Cyan, Magenta, Yellow, Back
- được tạo ra bằng cách nhúng một phần màu với một số bước sóng ánh sáng và  phản ánh lên nhau
- sử dụng trên các vật liệu vật lý: ảnh, báo, tạp chí, các tài liệu in

---
layout: image-right
image: assets/color-wheel.png
---
### Color wheel & Color Schemes 
(Bánh xe màu & Bảng màu)

Bánh xe màu sắc họat động ntn

- Bánh xe màu sắc chỉ ra mối quan hệ giữa các màu
- Có 12 màu chính trong bánh xe màu
    - Primary colors: red, yellow, blue
    - Secondary colors: green, orange, purple
    - Tertiary colors: blue-green, red-violet, …

---
layout: image-right
image: assets/color-wheel-picker.png
---
<style>
  .slidev-layout.slidev-page-10 + div {
    background-size: contain !important;
  }
</style>

Vì sao nên biết về color wheel ?

- giúp tạo đúng bảng màu
- thêm các màu vào bảng màu
- nhất quán trong màu sắc

Warm and Cool Colors

Bánh xe màu có thể chia thành màu ấm và màu lạnh → color temperature

Mỗi loại màu cho các loại cảm giác khác nhau

- Màu ấm (red through yellow): ấm cúng, năng lượng

- Màu lạnh (blue to green to purple): bình tĩnh, êm đềm, độc lập

---
layout: image-right
image: assets/fonts.png
---
<style>
  .slidev-layout.slidev-page-11 + div {
    background-size: contain !important;
  }
</style>

## Working with Fonts
### Font psychology
- font say about you, your business
- não người phản ứng với font tương tự màu sắc
- serif typeface: traditional, respectable
- sans serif typeface: stable, modern

---

### Font pairing tips
### Resources
- fonts.google.com
- fontpair.com
- fontjoy.com

---
layout: image-right
image: assets/typo-hierarchy.png
---

<style>
  .slidev-layout.slidev-page-13 + div {
    background-size: contain !important;
  }
</style>

### Typographic hierarchy
- order of importance, reader easily navigate the content
- show important info to focus on
- Key factors: typeface, size, weight, line-height, letter-spacing, color, letter-case

---

### Web fonts
- type of fonts: web safe fonts, system fonts
- system fonts: Arial, Times New Roman, Verdana, Geogia
- web fonts: Open Sans, Roboto

---

### Convert fonts to curves
Use when:
- logo design
- co-editing
- custom existing font

---

## Working with Icons
## User Experience Design
## 3 Phases of a Sales Funnel
## 4 Sales Funned Stages
## Macro/Micro Conversions
## Stages of Market Sophistication
## Lead Generation Funnel
## Digital Product Funnel
## 7 Principles of Influence
## Age Based Influence Triggers
## Gender Influence Triggers
## Interest Based Marketing