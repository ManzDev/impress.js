# Repo for learning Impress.js

- Official repo: https://github.com/impress/impress.js/
- Author: @Bartaz & @henrikingo

## First steps

1. Edit ``index.html``.
    * Exist a convenient preprocessor template: ``index.pug``. Compile with ``pug --pretty index.pug``.
2. Include ``js/impress.min.js`` (full framework with all plugins).
    * Exist a minimal ``js/impress-core.min.js`` and specific plugins (``plugins folder``).
3. Include ``css/impress.base.min.css`` for a minimal and basic styles.
    * Optional: Include ``css/darkgrey.theme.min.css`` for a dark theme or create your own theme.

- DEMO: [https://manzdev.github.io/impress.js/](https://manzdev.github.io/impress.js/)

## Don't forget

1. Edit metadata (*title, description and author*)
2. Div #impress contain all slides
3. Every .step is a slide
4. Configure your data-x, data-y, data-z slides
5. Place #overview if you need it.
