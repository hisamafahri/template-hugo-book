# Customization

To quickly customize the docs as you want, you can easily write a the corresponding file as listed in the [theme source code](https://github.com/alex-shpak/hugo-book/tree/main/layouts/_partials/docs) locally in the [`layouts/`](https://github.com/hisamafahri/template-hugo-book/tree/master/layouts) folder.

## Example

For example, I want to change the copyright section to not display the site name.

- I identify the component in [the source code](https://github.com/alex-shpak/hugo-book/blob/main/layouts/_partials/docs/copyright.html), which is `layouts/_partials/docs/copyright.html`.
- Then, I create the exact same file in the repository with the same path and filename (`layouts/_partials/docs/copyright.html`)
- Then I made the adjustment in that `copyright.html` file.
- _Voila!_, the copyright section now uses my custom `copyright.html` file.
