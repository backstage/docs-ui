# Backstage UI Documentation

This repository contains the generated static documentation site for [Backstage UI](https://ui.backstage.io), the React and TypeScript design system for Backstage.

The documentation covers installation, components, design tokens, hooks, and release notes. The UI library itself is maintained in the [Backstage monorepo](https://github.com/backstage/backstage); this repository contains the published documentation output.

## Browse the documentation

Visit [ui.backstage.io](https://ui.backstage.io) for the live site.

To preview this static site locally, run a web server from the repository root:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Install Backstage UI

Backstage includes Backstage UI by default. In a Backstage app or plugin that does not already include it, install the package from the relevant package directory:

```bash
yarn add @backstage/ui
```

Import the global stylesheet once in your application entry point:

```tsx
import '@backstage/ui/css/styles.css';
```

Then import the components you need:

```tsx
import { Button } from '@backstage/ui';
```

See the [installation guide](https://ui.backstage.io/get-started/installation) for details.

## Documentation sections

- [Components](https://ui.backstage.io/components)
- [Design tokens](https://ui.backstage.io/tokens)
- [Hooks](https://ui.backstage.io/hooks)
- [Changelog](https://ui.backstage.io/changelog)

## Contributing

Documentation and library source changes are made in the [Backstage monorepo](https://github.com/backstage/backstage). Read the [contributing guide](https://github.com/backstage/backstage/blob/master/CONTRIBUTING.md) before submitting changes.

## License

Backstage UI is licensed under the [Apache License 2.0](https://github.com/backstage/backstage/blob/master/LICENSE).
