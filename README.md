# Publishing to github npm registry

* Generate auth token at https://github.com/settings/tokens, check "repo" and "write:packages"
* Create ~/.npmrc file, add this lines:
```
//npm.pkg.github.com/:_authToken=INSERT_AUTH_TOKEN
@orbitaloyster:registry=https://npm.pkg.github.com
```
* Update package.json (replace "package-template" with actual package name)
* run ```npm publish```

# Installing package:

Important: ~/.npmrc file is also required to **install** packages from github repo

```bash
npm install @orbitaloyster/my-package
```

# License

[MIT](LICENSE)
