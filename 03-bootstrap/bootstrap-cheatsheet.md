# Bootstrap cheat sheet — NestFinder project

---

## Margin & padding

| Class | Meaning |
|---|---|
| `ms-auto` | margin start (left) |
| `me-auto` | margin end (right) |
| `mx-auto` | margin left + right |
| `my-auto` | margin top + bottom |
| `mt-` | margin top |
| `mb-` | margin bottom |
| `py-5` | padding top + bottom |
| `px-` | padding left + right |

---

## Layout & grid

| Class | Meaning |
|---|---|
| `container` | centered, max-width wrapper |
| `container-fluid` | full width wrapper |
| `row` | horizontal grid row |
| `g-4` | gap between grid columns |
| `col-12` | full width column |
| `col-md-4` | 3 columns on medium screens |
| `col-md-6` | 2 columns on medium screens |
| `col-lg-4` | 3 columns on large screens |

---

## Navbar

| Class | Meaning |
|---|---|
| `navbar` | base navbar class |
| `navbar-expand-lg` | collapses below lg screens |
| `navbar-brand` | brand logo or name |
| `navbar-toggler` | hamburger button |
| `navbar-toggler-icon` | hamburger icon inside button |
| `navbar-collapse` | collapsible link wrapper |
| `navbar-nav` | nav links list |
| `nav-item` | individual list item |
| `nav-link` | clickable link inside nav |

---

## Typography

| Class | Meaning |
|---|---|
| `display-5` | large hero heading |
| `fw-bold` | font weight bold |
| `lead` | larger intro paragraph |
| `text-muted` | faded text (light backgrounds) |
| `text-light` | light text (dark backgrounds) |
| `text-center` | center align text |
| `text-decoration-none` | removes underline from links |

---

## Buttons

| Class | Meaning |
|---|---|
| `btn` | base button class |
| `btn-primary` | solid blue button |
| `btn-outline-primary` | outlined blue button |
| `w-100` | full width button |

---

## Cards

| Class | Meaning |
|---|---|
| `card` | base card class |
| `card-img-top` | image at top of card |
| `card-body` | content area inside card |
| `card-title` | heading inside card body |
| `h-100` | full height card |

---

## Badges

| Class | Meaning |
|---|---|
| `badge` | base badge class |
| `bg-primary` | blue badge |
| `bg-success` | green badge |
| `bg-warning` | yellow badge |
| `bg-danger` | red badge |
| `text-dark` | dark text on light badges |

---

## Forms

| Class | Meaning |
|---|---|
| `form-control` | styled text input |
| `form-select` | styled dropdown |
| `input-group` | groups input + button together |

---

## Backgrounds

| Class | Meaning |
|---|---|
| `bg-light` | light grey background |
| `bg-dark` | dark background |
| `text-light` | white text for dark backgrounds |

---

## Page structure

Every section follows this same pattern:

```html
<section class="py-5">
  <div class="container">
    <div class="row">
      <div class="col-">
        content...
      </div>
    </div>
  </div>
</section>
```

---

## Navbar structure

```html
<nav class="navbar navbar-expand-lg bg-light">
  <div class="container">
    <a class="navbar-brand">         <!-- brand -->
    <button class="navbar-toggler">  <!-- hamburger -->
      <span class="navbar-toggler-icon">
    <div class="collapse navbar-collapse">
      <ul class="navbar-nav mx-auto">
        <li class="nav-item">
          <a class="nav-link">       <!-- links -->
    <button class="btn">             <!-- CTA button -->
  </div>
</nav>
```

---

## Hero structure

```html
<section class="bg-light py-5">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <h1>                         <!-- headline -->
        <p class="lead">             <!-- subtext -->
      <div class="col-12 input-group">
        <input class="form-control"> <!-- location input -->
        <select class="form-select"> <!-- dropdown -->
        <button class="btn">         <!-- search button -->
    </div>
  </div>
</section>
```

---

## Cards grid structure

```html
<section class="py-5">
  <div class="container">
    <h2>                                 <!-- section heading -->
    <div class="row g-4">
      <div class="col-md-6 col-lg-4">   <!-- repeat x6 -->
        <div class="card h-100">
          <img class="card-img-top">     <!-- image -->
          <div class="card-body">
            <span class="badge">         <!-- For Sale / Rent -->
            <p class="fw-bold">          <!-- price -->
            <h5 class="card-title">      <!-- property name -->
            <p class="text-muted">       <!-- location -->
            <p class="text-muted">       <!-- bed/bath/sqft -->
            <button class="btn w-100">   <!-- view details -->
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
```

---

## Footer structure

```html
<footer class="bg-dark text-light py-5">
  <div class="container">
    <div class="row">
      <div class="col-md-4">        <!-- brand + tagline -->
      <div class="col-md-4">        <!-- quick links (a tags) -->
      <div class="col-md-4">        <!-- contact info -->
    </div>
    <hr>                            <!-- divider -->
    <p class="text-center">         <!-- copyright -->
  </div>
</footer>
```
