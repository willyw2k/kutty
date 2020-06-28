# Kutty

Kutty is a set of accessible and reusable components for building web applications. It uses Tailwind classes, which is an utility based CSS framework, for styling the components.

## Installation

```sh
npm i kutty --save
```

Tailwind CSS is not available in this package. Learn how to [install tailwind here](https://tailwindcss.com/docs/installation/).

## Usage

### For CSS

For importing the whole package:

```css
@import "tailwindcss/base";
@import "tailwindcss/components";
/* Add Kutty here */
@import "kutty";
@import "tailwindcss/utilities";
```

Or for importing any single component:

```css
@import "tailwindcss/base";
@import "tailwindcss/components";
/* Add Kutty here */
@import "kutty/src/button.css";
@import "tailwindcss/utilities";
```

### For JS

Place the following script tag before the closing body tag:

```html
<script src="https://cdn.jsdelivr.net/npm/kutty/dist/kutty.js"></script>
```

## Development

Clone the repo, install dependencies, and start the server locally.

```sh
git clone https://github.com/praveenjuge/kutty.git
cd kutty
npm i
npm start
```

Then open [`http://localhost:1313`](http://localhost:1313) in your browser.

| Scripts              | Description                                     |
| -------------------- | ----------------------------------------------- |
| `npm start`          | Starts a local Hugo server and Tailwind Watcher |
| `npm run production` | For generating production docs files            |

## Components

- [x] Alert
- [x] Avatar
- [x] Badge
- [x] Breadcrumb
- [x] Button
- [x] Card
- [x] Dropdown
- [x] Forms
- [x] List
- [x] Pagination
- [x] Tabs
- [ ] Collapse
- [ ] Modal
- [ ] Loading
- [ ] Toasts
- [ ] Tooltips
