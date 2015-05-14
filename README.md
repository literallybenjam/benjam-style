# BENJAM STYLE #

Core styling in CSS for websites. Uses Lato (via Google Fonts) and M+ 1mn.

BENJAM STYLE is aimed primarily at styling content, and not at determining layout. However, there are a few aspects to layout you might want to consider:

1. BENJAM STYLE sets `display: flex` on `<body>`. This shouldn't cause problems generally, but it means that margin-collapsing might not work as you expect.
2. `<body>` is given a `max-width` of `36rem`.
3. You can use the `data-benjam-float` attribute on any element to create floating content. The possible values are:
    * `left` positions the element to the left
    * `right` positions the element to the right
    * `clear` makes the element clear any previous floating content
    * `clear-left` and `clear-right` combine the functionality of the above
4. You can use the `data-benjam-full` attribute on header elements for a larger header.
5. By default, `<div>`s centre text.

You should include BENJAM STYLE before any layout-intensive stylesheets to ensure that the proper rules are overrided.
