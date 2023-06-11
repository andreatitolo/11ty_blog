---
layout: layouts/base.njk
eleventyExcludeFromCollections: true
---
# Credits

This blog was created using the [eleventy-base-blog v8](https://github.com/11ty/eleventy-base-blog) as a starter template.

Most of the updates to the site are done using VSCodium for basically everything.

## Inspirations and thanks

I took huge inspirations for the style and general philosophy behind this site from [Simone Silvestroni](https://simonesilvestroni.com/) and his [Minutes to Midnight website](https://minutestomidnight.co.uk). If you go to the latter you will see many similarities indeed (this page is almost identical, but I really liked how it was layed out by Simone). In general Simone's blog were an inspiration both for the design of this site and the ideas I will try to uphold while improving my blog.

[Silvia Maggi](https://silviamaggidesign.com/about/), [Aleksandr Hovhannisyan](https://www.aleksandrhovhannisyan.com/about/), and [Jan Boddez](https://jan.boddez.net/) for some design inspiration and actual content ideas for presentation pages.

As for eleventy itself, [Kevin Powell's video](https://www.youtube.com/watch?v=4wD00RT6d-g) was probably the most useful thing I had while approaching this SSG for the first time, together with [Jaydan Urwin's Eleventy Crash Course](https://www.youtube.com/playlist?list=PLtLXFsdHI8JTwScHvB924dY3PNwNJjjuW). Other super helpful examples I had were those gathered from [The 11ty Bundle](https://11tybundle.dev/).

# Site

Built with **Eleventy {{ eleventy.version }}**.

## Code

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

## Privacy

I don't collect any personal data and there is no analytics on this website, nor ads, tracking or similar. As for CSP and securityheaders, a [Security Headers Report is available](https://securityheaders.com/?q=www.archaeoramblings.com&followRedirects=on) (**Score: A**).

## Copyright

Content of this website is under the [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/).

<a href="https://nonbot.org/pledged/view/99536763-fcd6-4150-96b6-2203d7ee9b5f" target="_blank">
	<img style="height:128px;margin-top:10px;margin-bottom:10px;" src="https://nonbot.org/images/nonbot_pledged_logo.svg" alt="Human-made Content">
</a>


_<p class="small">Last update: {{ page.date | htmlDateString }}.</p>_