
# 🌐 Personal Portfolio (HTML & CSS)

##  Overview
This is my beginner portfolio webpage built using HTML and CSS.  
The goal of this project is not just to build a webpage, but to clearly understand how structure (HTML) and styling (CSS) work together.

---

##  What This Project Demonstrates
- HTML structure (headings, paragraphs, lists, images)
- CSS styling (colors, fonts, spacing)
- Layout using Flexbox
- Reusable design using classes
- Clean and readable UI design

---

##  How the Page is Structured

The page follows a structured layout:

```

Page
└── Container
├── Hero Section
├── About Section
├── Skills Section
├── Projects Section
├── Favorite Website Section
└── Footer

````

👉 This structure helps organize content in a logical and readable way.

---

##  What is `<div>`?

`<div>` is a container used to group elements together.

Example:
```html
<div class="section">
  <h2>Projects</h2>
</div>
````

👉 It does not have meaning by itself
👉 It becomes useful when combined with **class + CSS**

##  Why `.container` is Used

```html
<div class="container">
```

👉 It wraps the entire page and:

* centers content
* controls maximum width
* keeps layout clean

##  Hero Section (Flexbox Example)

```css
.hero {
  display: flex;
}
```

👉 This activates Flexbox

Before Flexbox:

```
Text
Image
```

After Flexbox:

```
Text        Image
```

👉 Flexbox arranges elements **side by side**

##  What is `.hero-text`?

```html
<div class="hero-text">
```

👉 It groups:

* heading
* paragraph

👉 So Flexbox treats them as **one unit**

##  Why `.section` is Reused

```html
<div class="section">
```

👉 Used for:

* About
* Skills
* Projects
* Favorite

Because all sections share:

* same background
* same padding
* same spacing

👉 This avoids repeating CSS (clean design)

##  Why Skills Use `<ul>` and `<li>`

```html
<ul class="skills-list">
  <li>HTML</li>
  <li>CSS</li>
</ul>
```

👉 Skills are naturally a **list of items**

HTML defines meaning
CSS makes them look like styled boxes


##  Projects Section (Cards)

Structure:

```
Projects Section
  └── Projects Container
        ├── Project Card
        └── Project Card
```

Example:

```html
<div class="project-card">
  <h3>Project Title</h3>
  <p>Description</p>
</div>
```

 Each card groups:

* title
* description

 Cards are reusable UI components

##  Key Concepts Learned

* HTML = structure (what things are)
* CSS = styling (how things look)
* Margin = space outside elements
* Padding = space inside elements
* Class = reusable styling
* ID = unique styling
* Flexbox = layout system for arranging elements

##  Why This Structure Works

The page follows a natural flow:

1. Hero → introduction
2. About → description
3. Skills → capabilities
4. Projects → work
5. Favorite → personal touch
6. Footer → closing
 This makes the page easy to read and understand

##  Future Improvements

* Add more projects
* Improve design with advanced Flexbox
* Add buttons and interactivity
* Make it fully responsive

---

## 📷 Preview

(Add screenshot here later)










