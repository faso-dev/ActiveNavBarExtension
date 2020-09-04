# NavBarExtension
Just an helper to set the current menu active

# Requirements
- Symfony app 
- PHP > 7.2
  
# Use cases

Juste clone this repo in your src/Twig dir and remove the README.md file.
After doing this, the extension is automatically activated and you can start using it as follows:

```twig
<li class="{{ active_route('realisation') }}">
  <a href="{{ path('realisation') }}">
    <i class="fa fa-trophy"></i> Réalisations
  </a>
</li>
<li class="{{ active_route(['blog_index', 'blog_post_show']) }}">
  <a href="{{ path('blog_index') }}">
    <i class="fa fa-newspaper-o"></i> Blog
  </a>
</li>
```

# How to contribute ?

Juste clone this repo, do your edit, make a pull request
