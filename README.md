# Dropshipping Website

This repository contains files for a basic dropshipping website. You can view the static HTML or upload the provided Shopify theme.

## Static pages

The `site/` directory includes standalone HTML pages:

- `index.html` - Home page with a short introduction.
- `products.html` - Listing of sample products.
- `contact.html` - Contact information.

All pages share a common stylesheet `style.css`.

## Shopify theme

The `shopify-theme/` directory mirrors the same content using Shopify's Liquid template structure. To use it:

1. Zip the contents of `shopify-theme/` so that the `assets/`, `layout/`, and `templates/` folders are at the root of the archive.
2. In your Shopify admin, go to **Online Store > Themes > Add theme** and upload the zipped file.
3. Create new pages and assign them the `contact` or `products` templates to display those pages.

This provides a minimal theme that can be customized further within Shopify.
