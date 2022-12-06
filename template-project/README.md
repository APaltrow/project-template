# Template

This is a template for starting a project with all initial config.

## Dependencies & Config

- Typescript : _"^4.9.3"_

- Sass : _"^1.56.1"_

- Axios : _"^1.2.0"_

- Redux : _"^8.0.5"_ + Tool Kit : _"^1.9.1"_

- Router : _"^6.4.4"_

- Generate React CLI : _"^8.0.1"_

## Setup

```javascript

git clone https://github.com/APaltrow/project-template.git
```

```javascript
npm install
```

## Features

- Auto generation with _[Generate React CLI](https://github.com/arminbro/generate-react-cli)_ :

  - Components
  - Layouts
  - Pages

---

**COMPONENT** : _Auto generate a new folder with :_

- **Index file** with basic re-export .tsx
- **Main component file** .tsx _(with style imports + interface + export )_
- **Style file** .module.scss with necessary imports _(variables + mixins)_

**LAYOUT** : _Auto generate a new folder with :_

- **Layout file** .tsx _(with style imports + interface + export default)_
- **Style file** .module.scss

**PAGE** : _Auto generate a new folder with :_

- **Page file** .tsx _(with style imports + interface + export default)_
- **Page file** .module.scss

**Reconfiguration** is available for Component in _( /template-project/templates/default )_ folder.

Simply edit the files and it will be auto-applied to the config.

Necessary not to edit the 'TemplateName' part - it will cause a script error.

Script is configured like this :

```javascript

COMPONENT:

npm run component NameComponent

// name for component here *NameComponent* => creates a component in the corresponding folder

LAYOUT:

npm run layout NameLayout

// name for layout here *NameLayout* => same for layout

PAGE:

npm run page NamePage

// name for page here *NamePage* => same for page

```

---

- SASS

  - Normalize
  - Basic scss functions
  - Custom mixins for color and grids
  - Roboto Fonts - applied as default

- Configured router (hash)

- Configured & ready-to-use file structure
