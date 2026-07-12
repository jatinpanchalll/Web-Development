# CSS (Cascading Style Sheets)

CSS (Cascading Style Sheets) is used to style and design HTML web pages.

It controls the appearance, layout, colors, fonts, spacing, animations, and responsiveness of a website.

CSS makes websites visually attractive and user-friendly.

---

# What is CSS?

CSS stands for **Cascading Style Sheets**.

It is used to style HTML elements.

CSS controls:

- Colors
- Fonts
- Layout
- Spacing
- Animations
- Responsive Design

Without CSS, websites look plain.

---

# Why CSS?

HTML creates the structure.

CSS makes it beautiful.

Example

```
HTML

↓

Structure

↓

CSS

↓

Design

↓

JavaScript

↓

Functionality
```

---

# Features of CSS

- Easy to Learn
- Reusable Styles
- Responsive Design
- Better User Experience
- Fast Development
- Cross Browser Support

---

# CSS Syntax

```css
selector{

property: value;

}
```

Example

```css
h1{

color: blue;

font-size: 40px;

}
```

---

# Ways to Add CSS

## Inline CSS

```html
<h1 style="color:red;">
Hello
</h1>
```

---

## Internal CSS

```html
<style>

h1{

color:red;

}

</style>
```

---

## External CSS (Recommended)

```html
<link rel="stylesheet" href="style.css">
```

---

# CSS Selectors

- Universal Selector (`*`)
- Element Selector
- Class Selector (`.`)
- ID Selector (`#`)
- Group Selector
- Descendant Selector
- Child Selector
- Adjacent Selector

Example

```css
#title{

color:red;

}

.card{

background: white;

}
```

---

# Colors

```css
color:red;

color:#ff0000;

color:rgb(255,0,0);

color:hsl(0,100%,50%);
```

---

# Background

```css
background-color

background-image

background-size

background-repeat

background-position
```

---

# Text & Fonts

```css
font-family

font-size

font-weight

font-style

text-align

text-decoration

line-height
```

---

# Box Model

Every HTML element follows the Box Model.

```
Margin

↓

Border

↓

Padding

↓

Content
```

Example

```css
padding:20px;

border:2px solid black;

margin:15px;
```

---

# Display Property

```css
block

inline

inline-block

none

flex

grid
```

---

# Position

```css
static

relative

absolute

fixed

sticky
```

---

# Flexbox

Common Properties

```css
display:flex;

justify-content

align-items

flex-direction

flex-wrap

gap
```

---

# Grid

Common Properties

```css
display:grid;

grid-template-columns

grid-template-rows

gap
```

---

# Responsive Design

Media Query

```css
@media(max-width:768px){

}
```

Used for mobile-friendly websites.

---

# Transitions

```css
transition:0.5s;
```

---

# Transform

```css
translate()

rotate()

scale()

skew()
```

---

# Animations

```css
@keyframes

animation-name

animation-duration

animation-delay

animation-iteration-count
```

---

# Pseudo Classes

Examples

```css
:hover

:active

:first-child

:last-child

:nth-child()
```

---

# Pseudo Elements

```css
::before

::after

::selection

::first-letter
```

---

# Advantages of CSS

- Reusable Code
- Better UI
- Responsive Websites
- Faster Development
- Easy Maintenance
- Separation of Structure and Design

---

# Disadvantages

- Browser Compatibility Issues
- Large Stylesheets become difficult to manage
- Specificity conflicts

---

# Important Notes

- CSS styles HTML.
- External CSS is recommended.
- Flexbox is one-dimensional.
- Grid is two-dimensional.
- Box Model is one of the most important concepts.
- Media Queries make websites responsive.

---

# Common Mistakes

❌ Using IDs everywhere

❌ Overusing !important

❌ Ignoring Box Model

❌ Not making website responsive

❌ Writing duplicate CSS

---

# Interview Questions

## Basic

- What is CSS?
- Difference between Inline, Internal and External CSS?
- What is Box Model?
- Difference between id and class?

## Intermediate

- Difference between Flexbox and Grid?
- What is Position?
- Explain Specificity.
- What is z-index?

## Advanced

- What are Media Queries?
- Difference between relative and absolute?
- Difference between display:none and visibility:hidden?
- What is CSS Specificity?

---

# Mini Projects

- Profile Card
- Spotify Clone
- Sidebar Menu
- Pricing Card
- Landing Page
- Animated Button

---

# Quick Revision

- CSS = Cascading Style Sheets
- HTML = Structure
- CSS = Design
- JavaScript = Functionality
- Box Model = Margin → Border → Padding → Content
- Flexbox = 1D Layout
- Grid = 2D Layout
- Position = Static, Relative, Absolute, Fixed, Sticky
- Media Query = Responsive Design
- Animation = @keyframes

---

# Author

**Jatin Panchal**
GitHub:
https://github.com/jatinpanchalll