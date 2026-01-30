# Tabler theme

Custom Drupal theme built on [Tabler UI](https://docs.tabler.io/ui/getting-started/installation) — a responsive, modern dashboard and admin interface.

## Requirements

- Drupal 10 or 11
- Tabler assets are loaded from CDN (no build step required)

## Installation

1. Ensure the theme is in `web/themes/custom/tabler/`.
2. Go to **Appearance** and enable **Tabler**.
3. Set Tabler as the default theme (or use it as the admin theme).

## Regions

| Region         | Description                          |
|----------------|--------------------------------------|
| Header         | Site branding / logo (navbar brand)  |
| Navbar         | Top navigation links                 |
| Sidebar        | Vertical sidebar navigation          |
| Page header    | Optional page title / breadcrumb     |
| Content        | Main content                         |
| Sidebar second | Right sidebar                        |
| Footer         | Footer content                       |

## Layouts

- **With sidebar**: Place blocks in **Sidebar** and **Header** for the Tabler vertical sidebar layout (dark sidebar).
- **Without sidebar**: Place blocks in **Header** and **Navbar** for the horizontal navbar layout.

## Tabler UI

- [Installation](https://docs.tabler.io/ui/getting-started/installation)
- [Layout & page layouts](https://docs.tabler.io/ui/layout/page-layouts)
- [Components](https://docs.tabler.io/ui/components/)
- [Preview](https://preview.tabler.io)

## Customization

- Override templates in `templates/` as needed.
- Add or adjust CSS in `css/theme.css`.
- Tabler CSS/JS are loaded from `cdn.jsdelivr.net`; to use a local build, edit `tabler.libraries.yml` and point to local files.
