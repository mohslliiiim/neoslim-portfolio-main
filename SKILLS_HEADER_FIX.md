# Skills Page Header Fix

## Issue
The skills page has a duplicate header section (lines 480-493) that needs to be removed because the page already has the proper navigation header from index.html.

## Solution
Remove lines 480-493 and update line 478:

**Current (lines 478-494):**
```html
<div class="wrapper">

  <!-- HEADER -->
  <header>
    <p class="eyebrow">// portfolio · compétences & projets</p>
    <h1>
      <span class="name">MOHAMED</span><br>
      <span class="accent">SLIMANI</span>
    </h1>
    <p class="subtitle">Développeur Full-Stack · Jeux Vidéo · Design · Automatisation</p>
    <div class="header-tags">
      <span class="tag tag-a">Montréal, QC</span>
      <span class="tag tag-b">Trilingue FR / EN / AR</span>
      <span class="tag tag-c">DEC Jeux Vidéo 2025</span>
    </div>
  </header>

  <!-- TECH SKILLS -->
```

**Replace with:**
```html
<div class="wrapper" style="padding-top: 120px;">

  <!-- TECH SKILLS -->
```

This removes the duplicate header and adds proper spacing since the navigation header is already present at the top of the page.
