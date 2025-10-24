# Amazon seller landing theme

This repository now contains a Shopify-compatible theme version of the "Sell on Amazon" landing page. The layout and styling from the original static HTML/CSS implementation have been converted into a single customizable homepage section.

## Structure

```
layout/theme.liquid      # Global HTML shell that loads fonts and the compiled stylesheet
sections/homepage.liquid # Dynamic section that renders the landing page content
templates/index.liquid   # Homepage template that pulls in the landing page section
assets/styles.css        # Styling extracted from the original static page
config/settings_schema.json # Minimal theme settings stub
```

## Getting started

1. Zip the repository contents (or use Shopify CLI's `theme push` from this directory).
2. Upload the theme archive to your Shopify store (Online Store → Themes → Upload theme) or push with the CLI.
3. In the theme editor, open the **Home page** template. The "Amazon seller landing" preset is available for quick setup, and every textual element can be customized through the section settings and blocks.
4. Replace the default imagery and update links or copy to match your brand.

Once published, this theme will display the landing experience as the store's homepage.
