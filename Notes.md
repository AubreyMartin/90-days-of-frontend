Class notes and topics covered

frontend-90-days
├── 01-html/
├── 02-css/
├── 03-bootstrap/
├── 04-javascript/
├── 05-jquery/
├── 06-react/
├── 07-material-ui/
├── 08-semantic-ui/
├── 09-ant-design/
├── 10-redux/
├── 11-react-redux/

# File Naming Structure

## HTML

01-html/
├── 01-html-basics.html
├── 02-headings-paragraphs.html
├── 03-links-images.html
├── 04-lists.html
├── 05-tables.html
├── 06-forms.html
├── 07-semantic-html.html

## CSS

02-css/
├── 01-css-basics.html
├── 02-selectors.html
├── 03-flexbox.html

## JavaScript

04-javascript/
├── 01-js-basics.html
├── 02-dom.html
├── 03-events.html

## Commit Naming

Day 01: HTML basics
Day 02: Forms and inputs

# ========================================

class videos:
drive: https://drive.google.com/drive/folders/1xsC4pqkstR4jJbzbkqQFF2QBZXQd1xzdf

###

Day 1
Fri 27th march
Class 1
concept:

---

Elements
<> open tag
</> close tag

# str of HTML

html - root elements
head - info about doc
body - output
title
h1 to h6
p
=========
lists
———-
ul unordered list
ol ordered list
dl description list

# ========================================

###

Day 2
Sat 28th march
Class 2
concept:

---

=========

Table
———-
thead
tr-th (table row - table heading)
tbody
tr-td (table row - table data)
=========

Elements
———
paired elements
———
<> open tag
</> close tag

unpaired/ self closing / void elements
———
</>
<img/>

=========
Attributes

---

addtional info of en element
its add inside a open tag and an attributes are limited
main purpose:
name ="value"

## style attribute

add info to element
open tag
name="value"
works with every element

---

Properties

width =
hight =
color =
background color =
border =
text-align =

---

Element = structure
Property = control

whats the diffrence between attributes and style attributes?
ans:

# ========================================

###

Day 3
Sat 31st March
Class 3
concept:

---

====
Website layout

---

## div

is a part of a webpage

<div  style = "width: 10% ; height:10px; backgroundcolour: black; color: white; content align:center; ">
<div/>

Semantic elements
++====
meaningful elements

body;
header
section
footer

: Height always use px not percentage
: <br> is call a break its use for leave a line | moving to the next line.

:

# ========================================

###

Day 4
wed 1st April
Class 4
concept:

---

what is Semantic HTML?
Non Semantic vs Semantic

doctype html

Part of webpage

Semantic Elements

======================

meaningful elements

header

nav

footer

main

section

figure

figcaption

details

summary

article - news / blogs

aside - sidebar

# ========================================

###

Day 5
thu 2nd April
Class 5
concept:

---

intergarde

embed (<ifram> </ifram>)
img
svg
video
v att: controls

offline video

maps
pdf

# ========================================

###

Day 6
Fri 3rd April
Class 6
concept:

---

## form

used to collect data from user
action - if submitted
method - secure transfer data

## input

type

input : type
name : text
tel : phone
email : email
date : date
age: number
time:
datetime :
week :
month:
radio:
checkbox:
submit
button
reset
range
password
color
image
hidden
url
file

# ========================================

###

Day 7
sat 4rd April
Class 6
concept: HTML Css

---

Look and feel of a website
style
custom

## Properties.

## Types of CSS

1. inline CSS -
   every element - style attr -

2. Internal CSS
   webpage- style element -
3. External CSS
   webpage - .css - link - href rel (hyper reffrence, relation)

# ========================================

###

Day 8
Mon 6rd April
Class 8
concept: HTML Css

---

Box model
0.content
1.padding- inner space
2.border- end
3.margin- other space
--

## top, right, bottom, end

Content-box
Doesn't include padding / border inside widdht & height

Margin:
when: to create space between elements
why: to control layout and separation
best pratices: use for outer spacing and keep values consistent

Padding:
when: to create space inside the element
why: to improve readability and clickable area
best pratices: use for inner spacing and keep it consistent

Border:
when: to visually separate or highlight elements
why: to add structure and clarity
best pratices: keep it subtle and consistent (1px, same color)

notes:

1. Not need to use margin every time
2. best pratices is to add the padding and use box-sizing border-box so it don't distub the layout
3. use margin for outside spacing and padding for inside spacing

# ========================================

###

Day 9
Tue 7rd April
Class 9
concept: HTML Css

Display Properties
Inline : side by side not support W&H
block : one by one - takes full width
inline-block: side by side and supports W&H
none: not displayed

Block : p, div
inline: span, a

## inline and block is only for content not for layout

# Float:

---

Left - ltr (left to Right) child
clear- both
Right - rtl (Right to left)

# child

float: left
clear: both
display: table
clearfix: used to fix float collapsing issue

Defult css:

1. margin: 0;
2. padding: 0;
3. box-sizing: border-box;
4. font-family: sans-serif;

notes:

Issue with float:

1. border box : helps include padding & border inside width
2. box-sizing : controls how width & height are calculated
3. content box: default, adds padding & border outside
4. parent collapse issue (height becomes 0)

slector:
decented: parent child (space)
grouping: h1, p, div
gloab: \*

---

# ========================================

###

Day 10
wed 8th April
Class 10
concept: HTML Css

---

## Netflex website:

Strucher
Body
section calss: hero
header
div class logo
nav
header
section
body

Note:
Vh: Viweport height
bh:
px:

For class → use .classname in CSS
For element → just use the tag name (no dot)
. → class
no symbol → element

# ========================================

###

Day 11
Thu 9th April
Class 11
concept: HTML Css

---

## Reviwe of the project!

# ========================================

###

Day 12
fri 10th April
Class 12
concept: HTML Css

---

# Flex

---

alignment
-Height adjustment
Side by side
center

---

display: flex
justify-content: start | center | end | space-between | space-around | space-evenly
align-items: start | center | end | stretch | baseline
flex-direction: row | row-reverse | column | column-reverse
flex-wrap: nowrap | wrap | wrap-reverse

# ========================================

###

Day 13
Sat 11th April
Class 13
concept: HTML Css

---

Figma class

# ========================================

###

###

Day 14  
Mon 13th April  
Class 14  
Concept: HTML & CSS

---

# Positions

---

Static – default, normal flow (top/left don’t work)

Relative – moves from its own position, stays in normal flow

Absolute – positioned relative to nearest ancestor, removed from flow

Fixed – stays fixed on screen, does not move on scroll

Sticky – normal flow → becomes fixed when scrolling

top | right | bottom | left → used to move elements

---

# z-index

---

Stack order (layering)

Default: 0

Higher value → appears on top

Works only with positioned elements

# ========================================

###

###

Day 15  
Tue 14th April  
Class 15  
Concept: HTML & CSS

---

# Note

Same as Class 14

---

# Positions

---

Static – default, normal flow (top/left don’t work)

Relative – moves from its own position, stays in normal flow

Absolute – positioned relative to nearest ancestor, removed from flow

Fixed – stays fixed on screen, does not move on scroll

Sticky – normal flow → becomes fixed when scrolling

top | right | bottom | left → used to move elements

---

# z-index

---

Stack order (layering)

Default: 0

Higher value → appears on top

Works only with positioned elements

---

# Extra

---

background

object-fit: cover → covers entire container without distortion

# ========================================

###

###

Day 16  
Wed 15th April  
Class 16  
Concept: CSS

---

# Pseudo Classes & Elements

---

Pseudo Classes – special state of elements (use :)

Pseudo Elements – style specific part of elements (use ::)

---

# Common Pseudo Classes

---

:first-child  
:last-child  
:nth-child() → 1, even, odd  
:focus  
::placeholder

---

# Common Pseudo Elements

---

::first-line  
::first-letter  
::selection  
::before  
::after

---

# Color Codes

---

rgb() → red, green, blue

rgba() → rgb + opacity

hex → #ffffff

---

# ========================================

###

# ========================================

###

###

Day 17
Thu 16th April  
Class 17
Concept: CSS

---

Just Q&A

# ========================================

###

Day 18
Fri 17th April  
Class 18
Concept: CSS

---

CDN
Fonts
Icons

# SVG

Best way to use :

- download instead of
-
-
-

# ========================================

###

###

Day 19
Wed 18th April  
Class 19
Concept: CSS

---

###

Day 20  
Wed 20th April  
Class 20  
Concept: CSS

---

# Advanced CSS

---

# Rules

---

@media → responsive design  
@keyframes → animations  
@font-face → custom fonts

---

# Responsive Design

---

Adjust layout for different screen sizes

Important:

- Use breakpoints (e.g. 768px, 1024px)
- Mobile-first approach (start small → scale up)
- Use flexible units: %, rem, vw
- Avoid fixed widths

---

# Animations

---

Use @keyframes to define steps

Important:

- animation-name
- animation-duration
- animation-iteration-count
- animation-timing-function

Example:
@keyframes move {  
 from { transform: translateX(0); }  
 to { transform: translateX(100px); }  
}

---

# Transforms

---

translate → move element

rotate → rotate element

scale → resize element

skew → tilt element

Important:

- Does NOT affect layout (no space change)
- Often used with hover

---

# Transitions

---

Smooth change between states

Important:

- transition-property
- transition-duration
- transition-delay
- transition-timing-function

Example:
transition: all 0.3s ease;

---

# Extra Notes

---

- Use transform + transition together for smooth UI
- Prefer transform over top/left for better performance
- Keep animations fast (0.2s–0.5s)
- Don’t overuse animations (keep UI clean)

###

Day 21
Wed 21th April  
Class 21
Concept: CSS

---

## Animation

@keyframes name {
0%{}
100%{}
}
Why we use percentage?
:

types of keyframes:
keyframe: locations {
0% to 100%
}

keyframes: zoom, add more to it

note:
animation should me mentioned in the class properties

1. animation name
2. animation duration (imp)
3. animation timing function
4. animation iteration count
5. animation delay
6.

Day 22
Wed 22th April  
Class 22
Concept: CSS

---

## Review of code

Day 23
Thu 23th April  
Class 23
Concept: Responsive Design

---

@media
device based design

mobile - Default to 600px
tablet - 600px to 1000px
laptop - 1000px to default

# mobile first

min-width

from small to big

# Laptop first

max-width

## from big to small

note:
Always follow the patten
big to small or small to big

big: laptop : 1000px
tablet: below 1000px & above 600
small: mobile : 600px

---

Day 24
Fri 24th April  
Class 24
Concept: Bootstrap

---

Bootstrap:
its all predefined Props
Is a CSS Framework
JS plugins

# Install Bootstrap

CSS- Layout
JS- Action

---

bootstrap.css
bootstrap.min.css

Note:

1. Classname is important
2. Install the bootstrap
3.

bootstrap.min.css
bootstrap.bundle.min.js

## Concepts:

1. grid system
2. carousel : Slideshow
3. nav bar : Responsive Navbar
4. modal: dialog box
5. Offcanvas: side bar (hidden)
6. cards and forms

container- fixed
container-fluid-100%

m - margin
p- padding
text
bg
text-bg-

color name:
danger
primary
s

---

Day 25
Sat 25th April  
Class 25
Concept: BS

mobile first
min-width

---

## Grid System

================
row
col-12
col-6 col-6

# Responsive Breakpoint

===============================
xs- default-col-12
sm - min 576px - col-sm-12
md - min 768px - col-md-12
lg - min 992px- col-lg-12
xl - min 1200px- col-xl-12
xxl - min 1400px- col-xxl-12

123

## col-12 col-sm-12 col-md-6 col-lg-6 col-lx-4 col-xxl-4

1 1 2 2 3 3

col-md-6 col-xl-4

---

Day 26  
Mon 27th April  
Class 26  
Concept: Bootstrap

---

Build the project layout using Bootstrap

Watch reference website

---

Notes:

1. Use Bootstrap grid system (row, col)
2. Use container / container-fluid for layout
3. Use Bootstrap classes instead of custom CSS (mt, p, d-flex)
4. Keep layout responsive by default
5. Follow mobile-first structure

---

Day 27  
Tue 28th April  
Class 27  
Concept: Bootstrap

---

Today: Build navbar in multiple ways

Integrated CSS and used it

1. Hardcoding
2. Website snippet
3. Work in progress

---

Notes:

1. Use Bootstrap navbar component
2. Use flex utilities for alignment
3. Customize navbar with your own CSS
4. Use responsive toggle (hamburger menu)
5. Keep code clean and reusable

---

Week 5

Day 28 – Wed 29th April  
Class 28  
Concept: Bootstrap

---

Building cards for the watch website

Adding fonts

Making it responsive for mobile

---

Notes:

1. Use Bootstrap card component
2. Add images, title, and text inside cards
3. Use Google Fonts or custom fonts
4. Use grid system for responsive layout
5. Test on different screen sizes

---

Day 29 – Thu 30th April
Class 29
Concept: Bootstrap

---

Day 30 – Fri 1st May
Class 30
Concept: Bootstrap

---

Bootstrap walk around of the website and the tools classnames and akl the sections

Day 31 – Sat 2nd May
Class 31
Concept:

Week 6

Day 32 – Mon 4th May
Class 32
Concept: Projects

3 projects on web designing HTML CSS BS

1. Landing page - min 10 sections
2. Business Websites - 10+ pages
3. Web app Ecommers - (online store) ex amazon end to end
4.

Day 33 – Tue 5th May
Class 33
Concept:

Day 34 – Wed 6th May
Class 34
Concept:

Day 35 – Thu 7th May
Class 35
Concept:

Day 36 – Fri 8th May
Class 36
Concept:

Day 37 – Sat 9th May
Class 37
Concept:

Week 7

Day 38 – Mon 11th May
Class 38
Concept:

Day 39 – Tue 12th May
Class 39
Concept:

Day 40 – Wed 13th May
Class 40
Concept:

Day 41 – Thu 14th May
Class 41
Concept:

Day 42 – Fri 15th May
Class 42
Concept:

Day 43 – Sat 16th May
Class 43
Concept:

Week 8

Day 44 – Mon 18th May
Class 44
Concept:

Day 45 – Tue 19th May
Class 45
Concept:

Day 46 – Wed 20th May
Class 46
Concept:

Day 47 – Thu 21st May
Class 47
Concept:

Day 48 – Fri 22nd May
Class 48
Concept:

Day 49 – Sat 23rd May
Class 49
Concept:

Week 9

Day 50 – Mon 25th May
Class 50
Concept:

Day 51 – Tue 26th May
Class 51
Concept:

Day 52 – Wed 27th May
Class 52
Concept:

Day 53 – Thu 28th May
Class 53
Concept:

Day 54 – Fri 29th May
Class 54
Concept:

Day 55 – Sat 30th May
Class 55
Concept:

Week 10

Day 56 – Mon 1st June
Class 56
Concept:

Day 57 – Tue 2nd June
Class 57
Concept:

Day 58 – Wed 3rd June
Class 58
Concept:

Day 59 – Thu 4th June
Class 59
Concept:

Day 60 – Fri 5th June
Class 60
Concept:

Day 61 – Sat 6th June
Class 61
Concept:

Week 11

Day 62 – Mon 8th June
Class 62
Concept:

Day 63 – Tue 9th June
Class 63
Concept:

Day 64 – Wed 10th June
Class 64
Concept:

Day 65 – Thu 11th June
Class 65
Concept:

Day 66 – Fri 12th June
Class 66
Concept:

Day 67 – Sat 13th June
Class 67
Concept:

Week 12

Day 68 – Mon 15th June
Class 68
Concept:

Day 69 – Tue 16th June
Class 69
Concept:

Day 70 – Wed 17th June
Class 70
Concept:

Day 71 – Thu 18th June
Class 71
Concept:

Day 72 – Fri 19th June
Class 72
Concept:

Day 73 – Sat 20th June
Class 73
Concept:

Week 13

Day 74 – Mon 22nd June
Class 74
Concept:

Day 75 – Tue 23rd June
Class 75
Concept:

Day 76 – Wed 24th June
Class 76
Concept:

Day 77 – Thu 25th June
Class 77
Concept:

Day 78 – Fri 26th June
Class 78
Concept:

Day 79 – Sat 27th June
Class 79
Concept:

Week 14

Day 80 – Mon 29th June
Class 80
Concept:

Day 81 – Tue 30th June
Class 81
Concept:

Day 82 – Wed 1st July
Class 82
Concept:

Day 83 – Thu 2nd July
Class 83
Concept:

Day 84 – Fri 3rd July
Class 84
Concept:

Day 85 – Sat 4th July
Class 85
Concept:

Week 15 (Final Stretch)

Day 86 – Mon 6th July
Class 86
Concept:

Day 87 – Tue 7th July
Class 87
Concept:

Day 88 – Wed 8th July
Class 88
Concept:

Day 89 – Thu 9th July
Class 89
Concept:

Day 90 – Fri 10th July
Class 90
Concept:
