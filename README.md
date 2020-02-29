# Jekyll Theme

Live demo at https://jekyll-theme-minimal-resume.netlify.com/
-
![](https://img.shields.io/badge/jekyll-✓-blue.svg)
![](https://img.shields.io/badge/html5-✓-blue.svg)
![](https://img.shields.io/badge/sass-✓-blue.svg)
![](https://img.shields.io/badge/particle--js-✓-blue.svg)


# Color and Particle Customization

- Color Customization
  - Edit the `.sass` variables
- Particle Customization
  - Edit the json data in particle function in `app.js`
  - Refer to `Particle.js` for help


# Running locally

In order to compile the assets and run `Jekyll` locally you need to follow those steps:

1. Install Jekyll
2. Run `jekyll build`
3. Start and http-server in the folder `_site`



# Content

You can (and should) edit the `.html` files for adding your own information, icons, working experience, social links or whatever you want to add. I.e.:

```html
<a aria-label="My Github" target="_blank" href="https://github.com/murraco">
  <i class="icon fa fa-github-alt" aria-hidden="true"></i>
</a>
```