# Lito Default Template

The official default template for [Lito](https://github.com/Lito-docs/cli).

## Usage

This template is automatically used by Lito:

```bash
# Uses this template by default
lito dev -i ./your-docs

# Or explicitly specify it
lito dev -i ./your-docs --template github:Lito-docs/template
```

## Customization

### Fork & Modify

1. Fork this repository
2. Make your changes
3. Use your fork:

```bash
lito dev -i ./docs --template github:YOUR_USERNAME/lito-default-template
```

### Local Development

1. Clone this repo
2. Modify the template
3. Use it locally:

```bash
lito dev -i ./docs --template ./path/to/this/folder
```

## Structure

```
├── astro.config.mjs     # Astro configuration
├── package.json         # Dependencies
├── src/
│   ├── components/      # UI components
│   ├── layouts/         # Page layouts
│   ├── pages/           # Route templates
│   ├── styles/          # CSS styles
│   └── utils/           # Utility functions
└── public/              # Static assets
```

## Creating Your Own Template

1. Copy this template as a starting point
2. Modify components, layouts, and styles
3. Push to GitHub
4. Use with: `--template github:you/your-template`

### Requirements

A valid Lito template must have:
- `astro.config.mjs`
- `package.json` with Astro dependencies
- `src/pages/` directory for routing

## License

MIT
