---
layout: page
title: Index des recettes
lang: fr
---

# Index des recettes

## 🇬🇧 Recettes en anglais

<div class="recipe-grid">
  {% for recette in site.en %}
    <div class="recipe-card">
      <a href="{{ site.baseurl }}{{ recette.url }}">{{ recette.title }}</a>
    </div>
  {% endfor %}
</div>

## 🇫🇷 Recettes en français

<div class="recipe-grid">
  {% for recette in site.fr %}
    <div class="recipe-card">
      <a href="{{ site.baseurl }}{{ recette.url }}">{{ recette.title }}</a>
    </div>
  {% endfor %}
</div>

---
## Code source
📦 Le code source de cette archive de recettes est disponible sur [GitHub - Archive MD Repository](https://github.com/mattonem/archive-md)
