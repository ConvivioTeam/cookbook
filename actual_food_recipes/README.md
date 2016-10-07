---
recipes: {
  "aubergine_curry.md" : "Aubergine Curry",
  "vegetarian_paella.md" : "Vegetarian Paella",
  "easy-ice-cream.md": "Easy Ice Cream"
  }
---
# Actual Food Recipes

At Convivio, we're a company of foodies. We love to cook, and love to eat. In this section we'll gather some of our favourite recipes and ideas.

Here's what we love cooking:

<ul class="recipes">
{% for link, title in page.recipes %}
<li class="recipe"><a href="{{ link }}">{{ title }}</a></li>
{% endfor %}
</ul>
