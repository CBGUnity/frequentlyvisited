# frequentlyvisited
A tool for Project Managers or other to store webpages instead of using favorites
# Frequently Viewed Sites Template

A reusable, single-file HTML portal for organizing frequently used links by category. It includes responsive cards, search, category filtering, keyboard focus styling, and an empty-results state.

## Customize

1. Open `frequently-viewed-sites-template.html`.
2. Replace placeholders wrapped in double braces, for example `{{PORTAL_TITLE}}` and `{{HOME_URL}}`.
3. Rename `data-category` values and matching card headings.
4. Copy a `.link-item` anchor to add another link.
5. Copy an entire `<section class="card">` block to add another category.
6. Remove any sample cards or links you do not need.

## Placeholder convention

- `{{..._URL}}` = destination URL
- `{{..._LABEL}}` = human-readable link text
- `{{PORTAL_TITLE}}` = page heading
- `{{PORTAL_DESCRIPTION}}` = short description
- `{{FOOTER_TEXT}}` = footer message

## GitHub note

This template intentionally contains no company-specific, personal, SharePoint, Power BI, authentication, project, or vendor URLs from the source page. Before committing future changes, verify that no private URLs, tenant IDs, user IDs, access tokens, session parameters, or confidential project names have been added.
