# Modular Octicons
It's technically [GitHub Octicons](https://github.com/primer/octicons) but with the icon-per-file style

## Installation
```bash
npm install --save octicons-modular
# Or with yarn
yarn add octicons-modular
```

## Usage
```js
const markGithub = require('octicons-modular/icons/mark-github')
markGithub.svg()
// '<svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-mark-github" aria-hidden="true" ><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>'

// You could also use icons like this
const octicons = require('octicons-modular')
octicons.zap.svg({ scale: 2 })
// '<svg version="1.1" width="20" height="32" viewBox="0 0 10 16" class="octicon octicon-zap" aria-hidden="true" ><path fill-rule="evenodd" d="M10 7H6l3-7-9 9h4l-3 7z"/></svg>'
```

## Supported octicons
[[https://github.com/hiendv/octicons-modular/blob/master/octicons.png]]
[Octicons v6.0.1](https://github.com/primer/octicons/tree/v6.0.1/lib/svg). More with the preview at [GitHub Octicons](https://octicons.github.com/)

## Development
```bash
git clone https://github.com/hiendv/octicons-modular.git && cd octicons-modular
npm install
npm run dev

# Build?
npm run build
```

## Testing
```bash
npm test
```

## Contribution
Issues and PRs are welcome !