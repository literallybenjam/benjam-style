# BENJAM STYLE #

Core styling in CSS for websites. Uses Lato (via Google Fonts) and M+ 1mn.

BENJAM STYLE is aimed primarily at styling content, and not at determining layout. However, there are a few aspects to layout you might want to consider:

1. BENJAM STYLE sets `display: flex` on `<body>`. It also gives `<body>` a `max-width` of `36rem`.
2. You can use the `data-benjam-float` attribute on any element to create floating content. The possible values are:
    * `left` positions the element to the left
    * `right` positions the element to the right
    * `clear` makes the element clear any previous floating content
    * `clear-left` and `clear-right` combine the functionality of the above
