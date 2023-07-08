## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```


config do settings.json vscode
"emmet.syntaxProfiles"?{
    "javascript": "jsx"
}
"emmet.includeLanguages":{
    "javascript":"javascriptreact"
}

install @rocketseat/eslint-config -D
install prettier-plugin-tailwindcss -D

arquivo .eslintrc.json
add
{
  "extends": ["next/core-web-vitals", "@rocketseat/eslint-config/react"]
}

criar o arquivo prettier.config.js
module.exports = {
    plugin: [require('prettier-plugin-tailwindcss')],
  }
  