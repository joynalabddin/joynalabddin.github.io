# DevJoynal Blogger performance assets

These versioned assets are intended for the public Blogger site `https://ethicalhackerjoynal.blogspot.com/`.

## Current stable release: v1.0.1

```text
https://joynalabddin.github.io/assets/blogger/v1.0.1/noncritical.min.css
https://joynalabddin.github.io/assets/blogger/v1.0.1/noncritical.min.js
```

The same files are available through jsDelivr:

```text
https://cdn.jsdelivr.net/gh/joynalabddin/joynalabddin.github.io@v1.0.1/assets/blogger/v1.0.1/noncritical.min.css
https://cdn.jsdelivr.net/gh/joynalabddin/joynalabddin.github.io@v1.0.1/assets/blogger/v1.0.1/noncritical.min.js
```

Release `v1.0.0` remains available for rollback.

The CSS begins with the below-the-fold section styles from the Blogger theme. The JavaScript is opt-in: it only loads elements explicitly marked with `data-dj-delay-src` or `data-dj-widget-src`, so it does not change the existing theme unless the Blogger template adds those attributes.

Critical CSS, hero/LCP image loading, navigation, search, Blogger comments, and layout configuration remain in Blogger and must not be moved to this asset without visual and functional testing.
