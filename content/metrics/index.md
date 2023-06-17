---
layout: layouts/home.njk
---

# Site metrics

I'm trying to keep this website as lightweight as possible, with accessibility, usability, and sustainability in mind. There is still room for improvement, especially on my knowledge of things side, but for now I am happy with the results. Below there are some information and metricts regarding the site that might be of interest.

## Site info

Built with **Eleventy {{ eleventy.version }}**. Most of the updates to the site are done using VSCodium for basically everything.


## Code

This site uses the following:
- Markdown
- Nunjucks
- HTML ([Validated](https://validator.w3.org/nu/?doc=https://www.archaeoramblings.com/))
- CSS ([Validated](http://jigsaw.w3.org/css-validator/validator?lang=en&profile=css3svg&uri=https%3A%2F%2Fwww.archaeoramblings.com&usermedium=all&vextwarning=&warning=1) - inspired by [Simple CSS](https://simplecss.org/))
- Javascript
- [Code Repository on Github](https://github.com/andreatitolo/11ty_blog)
- Hosted on Netlify

## Site sustainability

- [Lighthouse Report](https://pagespeed.web.dev/analysis/https-www-archaeoramblings-com/9mnaxe13e8?form_factor=desktop)
- Homepage loads in 0.8 seconds and weights less than 20kb (uncompressed).
- Site uncompressed size is 18.7kb.
- 0.00g of CO2 [produced every time someone visits this web page](https://www.websitecarbon.com/website/archaeoramblings-com/).
- 100 score on [Ecograder](https://ecograder.com/report/bz66KdfL3waTP0p2FHFDungb).

## Accessibility

- Page content and the entire website is accessible with javascript turned off.
- [Wave Report](https://wave.webaim.org/report#/https://www.archaeoramblings.com/)

_<p class="small">Last update: {{ page.date | htmlDateString }}.</p>_