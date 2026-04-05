# bulma-tailwind

Bulma CSS classes implemented with Tailwind CSS v4.
You can use the classes you know from Bulma (.button, .card, .modal, .columns, etc.) but the style is generated with Tailwind v4 utilities.

## Why?
- To provide a familiar API for Bulma users while leveraging Tailwind's utility-first approach.

## Demo
You can see a [live demo](https://bulma-tailwind.pages.dev/) of the implemented classes in the `src/example` folder. It includes examples of elements, components, and form controls styled with Tailwind CSS.

## Installation

```bash
npm install bulma-tailwind
```

## Usage
Import the CSS into your project:

```css
@import "bulma-tailwind";
```

Or include the compiled file:

```html
<link rel="stylesheet" href="node_modules/bulma-tailwind/dist/bulma-tailwind.css">
```

Then use the Bulma classes as usual:

```html
<button class="button is-primary">Button</button>
<div class="card">
  <div class="card-content">
    <p class="title">Title</p>
  </div>
</div>
<div class="columns">
  <div class="column is-6">Column</div>
</div>
```

## Supported classes
- Elements: button, box, content, delete, icon, image, notification, progress, table, tag, title.

- Components: breadcrumb, card, dropdown, menu, message, modal, navbar, pagination, panel, tabs.

- Form: general (field, label, control, help), input, textarea, select, checkbox, radio, file.

- Layout: columns (grid), container, hero, section, level.

- Others: media object, footer.

## Customization
The package uses CSS variables defined in :root. You can override them:

```css
:root {
  --color-primary: #ff5722;
  --color-link: #2196f3;
  --color-info: #3e8ed0;
  --color-success: #48c78e;
  --color-warning: #ffe08c;
  --color-danger: #f14668;
  --color-light: #f5f5f5;
  --color-dark: #363636;
}
```

## License
MIT License

## Warnings
- This package is in early development. Not all Bulma classes are implemented yet, and some

## Want to contribute?
Feel free to open an issue or submit a pull request with your changes. Any help is appreciated!