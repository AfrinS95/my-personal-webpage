# HTML Concepts Explained

## What is `<head>`?

The `<head>` section contains information about the webpage.
It is not visible to users.

---

## What is `<title>`?

`<title>` defines the name of the webpage shown in the browser tab.

---

## What is `<meta>`?

Meta tags provide instructions to the browser.

Example:
`<meta charset="UTF-8">`

Meta tags do not appear on the page.
## What is `<meta>` in HTML?

**Definition:**  
The `<meta>` tag provides information about the webpage to the browser.

**Explanation:**  
The `<meta>` tag does not display anything on the webpage. Instead, it gives instructions to the browser about how to handle and display the page correctly.

---

## Simple Understanding

`<meta>` = information about the page, not content in the page

---

## Examples from the Code

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0"> 
1. <meta charset="UTF-8">

Purpose:
Defines how characters are interpreted on the webpage.

Explanation:
This tells the browser how to read and display text properly.

Why this matters:

Without it, some characters or symbols may not display correctly
It ensures proper support for different languages and symbols

UTF-8 supports:

English text
Symbols such as ₹, €, ©
Special characters and emojis
2. Viewport Meta Tag
<meta name="viewport" content="width=device-width, initial-scale=1.0">

Purpose:
Controls how the webpage is displayed on different screen sizes.

Explanation:

width=device-width sets the page width equal to the device screen width
initial-scale=1.0 sets the default zoom level

Why this is important:

Without it, the page may appear zoomed out on mobile devices
Layout may break on smaller screens
With it, the page becomes responsive and adjusts properly
Why <meta> is Inside <head>

The <meta> tag is placed inside the <head> section because:

It provides instructions to the browser
It is not part of the visible content
Types of Meta Tags (Basic Awareness)

Common meta tags include:

charset – defines character encoding
viewport – controls layout on mobile devices
description – used by search engines
author – defines the page author
keywords – used for SEO (less common now)
Key Points to Remember
<meta> provides settings for the webpage
It is not visible to users
It helps the browser display content correctly
It plays an important role in responsiveness and compatibility
One-Line Summary

The <meta> tag contains behind-the-scenes instructions that help the browser understand and display the webpage correctly.
---

## What is `<body>`?

The `<body>` contains everything visible on the webpage.

---

## What is `<div>`?

`<div>` is a container used to group elements together.

It helps organize content and apply styling using CSS.

---

## Why is structure important?

A webpage follows a logical order:

- Hero section (introduction)
- About section
- Skills section
- Projects section
- Footer

## What is `<html>`?

**Definition:**  
The `<html>` tag is the root element of a webpage.  
All content must be inside this tag.

**Example:**
```html
<html>
  ...
</html>
````

**Key Points:**

* It wraps the entire webpage
* It contains both `<head>` and `<body>`

---

## What is `<!DOCTYPE html>`?

**Definition:**
This tells the browser that the document is an HTML5 document.

**Example:**

```html
<!DOCTYPE html>
```

**Key Points:**

* Must be the first line
* Helps browser render correctly

---

## What is `<h1>` to `<h6>`?

**Definition:**
Heading tags are used for titles and section headings.

**Example:**

```html
<h1>Main Title</h1>
<h2>Subheading</h2>
```

**Key Points:**

* `<h1>` is most important
* Used for structure and readability

---

## What is `<p>`?

**Definition:**
The `<p>` tag is used for paragraphs of text.

**Example:**

```html
<p>This is a paragraph.</p>
```

**Key Points:**

* Used for content
* Improves readability

---

## What is `<a>`?

**Definition:**
The `<a>` tag is used to create links.

**Example:**

```html
<a href="https://google.com">Visit Google</a>
```

**Key Points:**

* `href` defines the link
* Can link to websites or sections

---

## What is `id`?

**Definition:**
An `id` is used to uniquely identify one element.

**Example:**

```html
<div id="projects"></div>
```

**Key Points:**

* Used once per page
* Can be used for navigation
* Used in CSS with `#`

---

## What is `class`?

**Definition:**
A `class` is used to group multiple elements for styling.

**Example:**

```html
<div class="section"></div>
```

**Key Points:**

* Can be reused
* Used in CSS with `.`
* Helps avoid repeating styles

---

## Difference Between `class` and `id`

**Class:**

* Reusable
* Used for styling multiple elements

**ID:**

* Unique
* Used for one specific element

---

## What is `margin`?

**Definition:**
Margin is the space outside an element.

**Example:**

```css
margin: 20px;
```

**Key Points:**

* Controls distance between elements
* Creates spacing between sections

---

## What is `padding`?

**Definition:**
Padding is the space inside an element.

**Example:**

```css
padding: 20px;
```

**Key Points:**

* Controls space inside a box
* Improves readability

---

## What is `border`?

**Definition:**
A border is an outline around an element.

**Example:**

```css
border: 1px solid black;
```

**Key Points:**

* Defines edges of a box
* Can be styled with color and thickness

---

## What is `display: flex`?

**Definition:**
Flexbox is used to arrange elements in a row or column.

**Example:**

```css
display: flex;
```

**Key Points:**

* Aligns items horizontally
* Controls spacing and alignment

---

## What is `justify-content`?

**Definition:**
Controls horizontal alignment in Flexbox.

**Example:**

```css
justify-content: space-between;
```

**Key Points:**

* Moves items left, right, or spaced
* Works only with Flexbox

---

## What is `align-items`?

**Definition:**
Controls vertical alignment in Flexbox.

**Example:**

```css
align-items: center;
```

**Key Points:**

* Aligns items vertically
* Works inside flex container

---

## What is `gap`?

**Definition:**
Gap adds space between items in Flexbox.

**Example:**

```css
gap: 20px;
```

**Key Points:**

* Cleaner than using margins
* Works in flex layouts

---

## What is `:hover`?

**Definition:**
Applies styles when mouse is over an element.

**Example:**

```css
:hover {
  color: red;
}
```

**Key Points:**

* Adds interactivity
* Used in buttons and cards

---

## What is `transition`?

**Definition:**
Adds smooth animation to changes.

**Example:**

```css
transition: 0.3s;
```

**Key Points:**

* Makes UI feel smooth
* Used with hover effects

---

## What is `transform`?

**Definition:**
Used to move or scale elements.

**Example:**

```css
transform: translateY(-5px);
```

**Key Points:**

* Moves elements visually
* Used for animations

````

