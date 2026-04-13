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
concept: HTML Css

---

# ========================================

###

###

Day 16
Wen 15th April
Class 16
concept: HTML Css

---

# ========================================

###
