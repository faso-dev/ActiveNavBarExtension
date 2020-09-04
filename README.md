# NavBarExtension
Just an helper to set the current menu active

# Requirements
- Symfony app 
- PHP > 7.2
  
# Use cases

Juste clone this repo in your Twig dir

```twig
<li class="{{ active_route('odds_realisation') }}">
  <a href="{{ path('odds_realisation') }}">
    <i class="fa fa-trophy"></i> Réalisations
  </a>
</li>
<li class="{{ active_route(['odds_blog_index', 'odds_blog_post_show']) }}">
  <a href="{{ path('odds_blog_index') }}">
    <i class="fa fa-newspaper-o"></i> Blog
  </a>
</li>
```

# How to contribute ?

Juste clone this repo, do your edit, make a pull request
