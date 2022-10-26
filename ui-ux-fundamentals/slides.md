---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://images.unsplash.com/photo-1612334001559-947862cc2202?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxjb2xsZWN0aW9uLXBhZ2V8M3w5NDczNDU2Nnx8ZW58MHx8fHw%3D&auto=format&fit=crop&w=1296&q=60
# background: https://source.unsplash.com/collection/94734566/1920x1080
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

# Outline
Why UI / UX matter ?

UI/UX là gì ?

Stages of development

Tìm hiểu về UI - “Graphic Design”
  - Tìm hiểu về màu sắc
  - Tìm hiểu về fonts
  - Tìm hiểu về Icons

Tìm hiểu về UX - "User Experience"
  - Lấy người dùng làm trung tâm
  - Hành trình của khách hàng
  - Mô hình phễu bán hàng

---

# Why UI / UX matter ?

Nếu bạn nghĩ làm web developer chỉ cần biết code, ai đưa gì làm nấy thì đó mà mindset chưa đúng.

Việc dev học về thiết kế UI/UX như là một nền tảng cơ bản để làm web developer, giúp bạn:

- hiểu về người dùng hơn, sản phẩm hơn
- hỗ trợ bộ phận thiết kế, nghiên cứu hành vi người dùng
- lựa chọn các kỹ thuật phù hợp hơn
- hoàn thành công việc tốt hơn
- dễ dàng hơn trong việc tự thiết kế sản phẩm riêng của mình


---

# UX vs. UI

---
layout: image-right
image: assets/ui-vs-ux.jpeg
---
<style>
  .slidev-layout.slidev-page-5 + div {
    background-size: contain !important;
  }
</style>
## UX (User Experience)

- Là: sự tương tác giữa khách hàng và công ty
- Dựa vào: 
  - thiết kế trực quan
  - tâm lý hành vi
  - các nghiên cứu khách hàng
- Áp dụng lên sản phẩm 
  - trang web
  - máy bán hàng tự động

## UI (User Interface)

- Là cái nhìn thấy và cảm nhận (look & feel)
- Là điểm tương tác giữa người dùng và sản phẩm trên thiết bị kỹ thuật số touch screen, touch pad)

---
layout: image-right
image: assets/stage-web-development.png
---
<style>
  .slidev-layout.slidev-page-6 + div {
    background-size: contain !important;
  }
</style>
# State of Web Development
## Design Stage

Big picture design overview: 
  - how does the website look like
  - functional, features

Answer questions:
1. Goals for the page
2. Goals for the user
3. Questions that users need to answer to in order to accomplish the goal
4. Emotions that we want to invoke

---

Wireframing
- Bản phát thảo sketch cho thấy phần tử nào ở đâu trong trang web
- Templates các loại page
- Color scheme cũng đc chọn ở bước này
- Tools: Adobe XD, Figma

---

## Coding Stage
Frontend development
- HTML: create and structure sections, paragraphs, heading, link, blockquotes, ...
- CSS: style elements: font styles, buttons, elements, …
- JS: make interactive

## Deployment Stage
Backend development
- make FE web possible - host the web
- consists: a server, application, database
---
layout: image-right
image: assets/psychology-color.png
---
<style>
  .slidev-layout.slidev-page-4 + div {
    background-size: contain !important;
  }
</style>


# Graphic Design
## Psychology of color 
<br />

### How does color work?

- Màu sắc ở mọi nơi.
- Chọn đúng màu sẽ giúp người dùng nhận biết thương hiệu
- Mỗi màu sẽ mang đến những cảm xúc khác nhau

---
layout: image-right
image: assets/psychology-color.png
---
<style>
  .slidev-layout.slidev-page-10 + div {
    background-size: contain !important;
  }
</style>

### Understanding color psychology
<br />

- Não người phản ứng với màu sắc
- Khi mắt tiếp xúc với màu sắc, mắt kết nối đến não và gửi tín hiệu tiết ra các loại hóc môn quyết định trạng thái của tâm trạng và cảm xúc
- Màu sắc được chọn phù hợp sẽ khiến người dùng phải hành động
- Chỉ trong 90s, người dùng sẽ phán xét về một sản phẩm, và từ 62% đến 90% là dựa trên màu sắc


---
layout: image-right
image: assets/psychology-color.png
---
<style>
  .slidev-layout.slidev-page-11 + div {
    background-size: contain !important;
  }
</style>

### Các màu sắc và cảm xúc đặc trưng:
<br />

- <span style="color: red; font-weight: 600;">Red</span>: confidence,  youth, power
- <span style="color: orange; font-weight: 600;">Orange</span>: friendly, warm, energetic
- <span style="color: yellow; font-weight: 600;">Yellow</span>: happiness, optimism, warmth
- <span style="color: green; font-weight: 600;">Green</span>: peace, growth, health
- <span style="color: blue; font-weight: 600;">Blue</span>: trust, security, stability
- <span style="color: purple; font-weight: 600;">Purple</span>: luxurious, creative, wise
- <span style="color: gray; font-weight: 600;">Black</span>: reliable, sophisticated (tinh vi), experienced
- <span style="color: white; font-weight: 600;">White</span>: simple, calm, clean


---
layout: image-right
image: assets/r-g-b.png
---
<style>
  .slidev-layout.slidev-page-7 + div {
    background-size: contain !important;
  }
</style>
### Lý thuyết về màu
<br />

#### <b>RGB</b>: Additive color mixing model

- <span style="color: red; font-weight: 600;">Red</span>, <span style="color: green; font-weight: 600;">Green</span>, <span style="color: blue; font-weight: 600;">Blue</span>
- Sử dụng: 
  - web design
  - only ads
  - digital-only files
- Mô tả: 
  - cách con người nhận dạng các màu
  - cách trộn màu
  - các màu tương phản
- Quản lý với 3 categories
  - primary colors
  - secondary colors
  - tertiary colors

---
layout: image-right
image: assets/cmyk.png
---
<style>
  .slidev-layout.slidev-page-8 + div {
    background-size: contain !important;
  }
</style>
<br />

#### CMYK: Subtractive color mixing model
<br />

- <span style="color: cyan; font-weight: 600;">Cyan</span>, <span style="color: Magenta; font-weight: 600;">Magenta</span>, <span style="color: Yellow; font-weight: 600;">Yellow</span>, <span style="color: gray; font-weight: 600">Back</span> 
- Là mô hình màu loại trừ, được tạo ra dựa trên cơ sở hấp thụ ánh sáng
- Màu được nhìn thấy là từ phần ánh sáng không được hấp thụ.
- Sử dụng: 
  - in ấn ảnh
  - báo, tạp chí
  - các tài liệu in

---
layout: image-right
image: assets/color-wheel.png
---
### Color wheel & Color Schemes 
<br />

#### Bánh xe màu sắc hoạt động ntn
<br />

- Mối quan hệ giữa các màu
- Có 12 màu chính
    - Primary colors: red, yellow, blue
    - Secondary colors: green, orange, purple
    - Tertiary colors: blue-green, red-violet, …

<br />

#### Vì sao nên biết về color wheel ?
<br />

- Giúp tạo đúng bảng màu
- Thêm các màu vào bảng màu
- Nhất quán trong màu sắc

---
layout: image-right
image: assets/color-wheel-picker.png
---
<style>
  .slidev-layout.slidev-page-15 + div {
    background-size: contain !important;
  }
</style>
#### Warm and Cool Colors
<br />

Bánh xe màu chia thành màu ấm và màu lạnh 

→ <b>color temperature</b>

Cảm giác:

- Màu ấm (red -> yellow)
  - ấm cúng
  - năng lượng

- Màu lạnh (blue -> green -> purple)
  - bình tĩnh
  - êm đềm
  - độc lập


#### Resources & Tools
- ColorZilla
- [coolors.co](https://coolors.co/)
---
layout: image-right
image: assets/fonts.png
---
<style>
  .slidev-layout.slidev-page-16 + div {
    background-size: contain !important;
  }
</style>

## Working with Fonts
<br />

### Font psychology
<br />

- Font say about you, your business
- Não người phản ứng với font
- Serif typeface (font chữ có chân) 
  - traditional
  - respectable
- Sans serif typeface (font chữ không chân) 
  - stable
  - modern

---
layout: image-right
image: assets/serif-vs-sans-serif.png
---
<style>
  .slidev-layout.slidev-page-17 + div {
    background-size: contain !important;
  }
</style>

### Mẹo chọn font đi cùng nhau 
<br />

- Dùng serif và sans-serif 
  - [compare link](https://www.canva.com/learn/serif-vs-sans-serif-fonts/)
- Tránh loại tương tự nhau
- Font size khác nhau
- Font weight khác nhau
- Sử dụng các font cùng font family (hay typeface)
- [(Examples)](fontjoy.com)

<br />


### Resources
- fonts.google.com
- myfonts.com
- fontjoy.com

---
layout: image-right
image: assets/typo-hierarchy.png
---

<style>
  .slidev-layout.slidev-page-18 + div {
    background-size: contain !important;
  }
</style>

### Typographic hierarchy
<br />

- Order of importance
- Reader easily navigate the content
- Show important info to focus on
- Key factors: 
  - typeface
  - size
  - weight
  - line-height
  - letter-spacing
  - color
  - letter-case

### Resources:
- [archetypeapp.com](https://archetypeapp.com/)
---
layout: image-right
image: https://cdn.pixabay.com/photo/2015/02/22/18/26/icons-645335_1280.png
---

<style>
  .slidev-layout.slidev-page-19 + div {
    background-size: contain !important;
  }
</style>

## Working with Icons

<br />

### Role of icons
<br />

- Đại diện phần lớn cách user điều hướng trang web / apps
- Icon sử dụng đúng cách sẽ hiệu dụng, dễ hớ, và nâng cao thiết kế cho trang web
- Lưu ý: icon nên đi kèm với chữ để giúp người dùng hiểu đúng ý nghĩa, trừ khi nó đã quá phổ biến với người dùng (như icon search)

---
layout: image
image: assets/icon-with-text.png
---
<style>
  .slidev-layout.slidev-page-20 {
    background-size: contain !important;
  }
</style>


---
layout: image-right
image: assets/styles-of-icon.png
---
### Styles of icons
<br />

- outline
- filled
- multicolor

<br />

### Resources
<br />

- [feathericons.com](https://feathericons.com/)
- [flaticon.com](https://www.flaticon.com/)
- [iconfinder.com](https://www.iconfinder.com/)

[Demo web](https://www.dashclicks.com/)
---

## UX Design

### Human-centered design approach
Nguyên tắc cốt lõi:

- Hiểu và chỉ ra vấn đề 
- Lấy con người làm trung tâm 
- Sử dụng Activity-Centered System Approach
- Nhanh chóng tạo mẫu và thí nghiệm & lặp lại
- Try to understand whole picture bởi vì thay đổi nhỏ ở một nơi sẽ ảnh hưởng nơi khác


---

## Customer Journey & Sales Funnel
<br />

### Customer Journey
- Chi tiết quá trình dẫn đến một khách hàng paying

<br />

### Sales Funnel
- Mô hình sử dụng mô tả ba giai đoạn của vòng lặp mua (buying cycle)

<br />

> Dù "Customer Journey" và "Sales Funnel" được biểu diễn khác nhau nhưng cùng nói lên một câu chuyện

---
layout: image
image: assets/customer-journey.png
---
<style>
  .slidev-layout.slidev-page-24 {
    background-size: contain !important;
  }
</style>

---
layout: image
image: assets/sale-tunnels.png
---
<style>
  .slidev-layout.slidev-page-25 {
    background-size: contain !important;
  }
</style>

---

## 3 Sales Funnel Phases
<br />

- TOF - Top of Funnel
- MOF - Middle of Funnel
- BOF - Bottom of Funnel

---
layout: image
image: assets/3-funnel-phases.png
---
<style>
  .slidev-layout.slidev-page-27 {
    background-size: contain !important;
  }
</style>

---


## 4 Sales Funnel Stages
<br />

- Awareness
- Interest
- Decision
- Action

---
layout: image
image: assets/4-sales-funnel-stages.png
---
<style>
  .slidev-layout.slidev-page-29 {
    background-size: contain !important;
  }
</style>

---

## Macro/Micro Conversions
<br />

### Macro conversation
- Hành động mà người dùng thực hiện cách hành động mục tiêu chính
  - thanh toán

### Micro conversation
- Hành động người dùng thực hiện dẫn đến hành động mục tiêu
  - thêm vào giỏ hàng 
  - thêm vào wishlist 
  - bookmark

---

# Discusion and Q & A


---

# Reference
- [UX Design Course Tutorial for Beginners: User Experience Design Fundamentals](https://www.youtube.com/watch?v=uL2ZB7XXIgg)

---

# Thank you