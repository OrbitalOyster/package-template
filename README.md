# Installation
Publishing package to github npm registry:
* Generate auth token at https://github.com/settings/tokens, check 'repo' and 'write:packages'
* Create ~/.npmrc file, add this line: //npm.pkg.github.com/:_authToken=INSERT_AUTH_TOKEN
* Update package.json (replace "package-template" with actual package name)
* run ```npm publish```

# Usage
Installing package:
```bash
npm install github:orbitaloyster/my-package
```

# License
[MIT](LICENSE)
