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
## Source Code
📦 The source code for this recipe archive is available on [GitHub - Archive MD Repository](https://github.com/mattonem/archive-md)
