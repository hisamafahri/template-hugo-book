# Footers

On building this project, I am customizing some part of the footer to accomodate my styles.

1. Copyright Section

In the [`copyright.html`](https://github.com/hisamafahri/template-hugo-book/blob/master/layouts/partials/docs/copyright.html), I've changed [original copyright footer](https://github.com/alex-shpak/hugo-book/blob/main/layouts/_partials/docs/copyright.html) to not display the site name.

```html
<small>{{ .Site.Copyright | .RenderString }}</small>
```

2. Pagination Section

I've removed the [original pagination section](https://github.com/alex-shpak/hugo-book/blob/main/layouts/_partials/docs/prev-next.html), by [render it empty](https://github.com/hisamafahri/template-hugo-book/blob/master/layouts/partials/docs/prev-next.html).

## Reverting My Customization

To revert my customizations above, you can either:

- Adjust the content to suits your needs (see the [customization](/tutorials/customization/) section to learn more)
- Delete my customization `.html` files to bring it back to the defaul
