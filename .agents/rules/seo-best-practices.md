# SEO Best Practices

When creating or modifying HTML pages for this project, always enforce the following Google SEO Starter Guide principles:

1. **Title and Meta Tags**:
   - Ensure every page has a unique and descriptive `<title>`.
   - Include `<meta name="description" content="...">` with a concise summary.
   - Set `<meta name="robots" content="index, follow" />`.

2. **Open Graph (Social Sharing)**:
   - Provide `og:title`, `og:description`, `og:image`, and `og:url` properties for every page.

3. **Structured Data (JSON-LD)**:
   - Include a `<script type="application/ld+json">` block in the `<head>` of content pages (like technical articles).
   - Use the appropriate schema type (e.g., `TechArticle`, `BlogPosting`, `WebSite`).

4. **Canonical URLs**:
   - Always specify a canonical URL for each page: `<link rel="canonical" href="https://troysuice.github.io/troy-smart-automation/[page].html" />`.

5. **Image Optimization**:
   - Always include descriptive `alt` text for `<img>` tags.

6. **Sitemap**:
   - If creating a new HTML page, proactively update `sitemap.xml` with the new URL and the current date.
