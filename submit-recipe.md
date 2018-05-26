---
layout: full-width
title:  Submit a Slime Recipe
permalink: /submit-recipe/
---

<p class="mb-3">Got a recipe for making Slime? Submit your recipe for <a href="/">slime-recipe.com</a> and get featured!</a>

<h3>Submit your Slime Recipe!</h3>
<form name="submit-recipe" method="POST" netlify action="/thank-you-recipe/">
  <div class="form-group">
    <label for="name">Name</label>
    <input type="text" class="form-control" id="name" aria-describedby="nameHelp" placeholder="Enter your name">
  </div>
    <div class="form-group">
    <label for="name">Email</label>
    <input type="email" class="form-control" id="email" aria-describedby="emailHelp" placeholder="Enter your Email">
  </div>
  <div class="form-group">
    <label for="exampleTextarea">Your Recipe</label>
    <textarea class="form-control" id="recipe" rows="3" placeholder="Enter your Recipe"></textarea>
  </div>
  <button type="submit" class="btn btn-primary">Submit Slime Recipe</button>
</form>

