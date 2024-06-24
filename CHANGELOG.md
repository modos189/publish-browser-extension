# Changelog

## v3.0.4

[compare changes](https://github.com/modos189/publish-browser-extension/compare/v3.0.2...v3.0.4)

## v3.0.2

[compare changes](https://github.com/modos189/publish-browser-extension/compare/v3.0.0...v3.0.2)

## v3.0.0

### 🚀 Enhancements

- Export publish method ([56b3231](https://github.com/modos189/publish-browser-extension/commit/56b3231))
- Implement CLI ([fdd369a](https://github.com/modos189/publish-browser-extension/commit/fdd369a))
- Upload to the chrome web store ([d8ce189](https://github.com/modos189/publish-browser-extension/commit/d8ce189))
- Upload to the Firefox Addon Store ([f637afc](https://github.com/modos189/publish-browser-extension/commit/f637afc))
- Added `--help` docs ([381ab91](https://github.com/modos189/publish-browser-extension/commit/381ab91))
- Add option for dry runs ([cb2b680](https://github.com/modos189/publish-browser-extension/commit/cb2b680))
- Use addon-server APIs instead of `web-ext` for Firefox ([#4](https://github.com/modos189/publish-browser-extension/pull/4))
- Publish to Edge Store ([#6](https://github.com/modos189/publish-browser-extension/pull/6))
- Create util for getting the chrome refresh token ([#9](https://github.com/modos189/publish-browser-extension/pull/9))
- Improve logging and CLI appearance ([#11](https://github.com/modos189/publish-browser-extension/pull/11))
- ⚠️ Refactor CLI to add `init` command ([#13](https://github.com/modos189/publish-browser-extension/pull/13))
- Read variables from `.env.submit` automatically ([#15](https://github.com/modos189/publish-browser-extension/pull/15))

### 🩹 Fixes

- Only require flag values when used ([37d4f03](https://github.com/modos189/publish-browser-extension/commit/37d4f03))
- Misc bug fixes ([#1](https://github.com/modos189/publish-browser-extension/pull/1))
- Export useful types for consumers ([c472eb7](https://github.com/modos189/publish-browser-extension/commit/c472eb7))
- Create temp `WEB_EXT_SOURCE_DIR` for Firefox publishing ([#3](https://github.com/modos189/publish-browser-extension/pull/3))
- **cli:** Exit with status code 1 on error ([48addd0](https://github.com/modos189/publish-browser-extension/commit/48addd0))
- Correct CWS publish API call ([b16c454](https://github.com/modos189/publish-browser-extension/commit/b16c454))
- Don't fail when signing listed firefox extensions ([713c1a1](https://github.com/modos189/publish-browser-extension/commit/713c1a1))
- Improve default value handling ([8cdcfb3](https://github.com/modos189/publish-browser-extension/commit/8cdcfb3))
- Support addon ids with the `<scope>@<name>` format ([#8](https://github.com/modos189/publish-browser-extension/pull/8))
- Ensure ZIP exists before uploading ([#12](https://github.com/modos189/publish-browser-extension/pull/12))
- Edge log not showing correctly ([3fa473f](https://github.com/modos189/publish-browser-extension/commit/3fa473f))
- Remove log ([d0a4723](https://github.com/modos189/publish-browser-extension/commit/d0a4723))
- Don't require all config to run `init` command ([89bfe5d](https://github.com/modos189/publish-browser-extension/commit/89bfe5d))
- Support node 20 in `engines` field in `package.json` ([#17](https://github.com/modos189/publish-browser-extension/pull/17))
- Include cli in export paths ([42c356a](https://github.com/modos189/publish-browser-extension/commit/42c356a))
- Report specific missing configurations ([#19](https://github.com/modos189/publish-browser-extension/pull/19))
- Fetch error typo ([#20](https://github.com/modos189/publish-browser-extension/pull/20))

### 📖 Documentation

- Mark stores as TODO ([385d286](https://github.com/modos189/publish-browser-extension/commit/385d286))
- Correct import for example usage ([3da1436](https://github.com/modos189/publish-browser-extension/commit/3da1436))
- Check firefox addons as done ([e8a26dd](https://github.com/modos189/publish-browser-extension/commit/e8a26dd))
- Fix typos in README ([e334144](https://github.com/modos189/publish-browser-extension/commit/e334144))
- Fix README typos ([a24c782](https://github.com/modos189/publish-browser-extension/commit/a24c782))
- Update README ([b25ccdc](https://github.com/modos189/publish-browser-extension/commit/b25ccdc))
- Update README ([320a526](https://github.com/modos189/publish-browser-extension/commit/320a526))
- Add `chrome-refresh-token` docs to README ([437f89e](https://github.com/modos189/publish-browser-extension/commit/437f89e))
- Update demo screenshot ([d2d785c](https://github.com/modos189/publish-browser-extension/commit/d2d785c))
- Add env section to README ([ff62b9b](https://github.com/modos189/publish-browser-extension/commit/ff62b9b))

### 🏡 Chore

- Initial project setup ([2f5d553](https://github.com/modos189/publish-browser-extension/commit/2f5d553))
- Cleanup tsc error output from vite ([aa51e69](https://github.com/modos189/publish-browser-extension/commit/aa51e69))
- Add .npmignore ([176e228](https://github.com/modos189/publish-browser-extension/commit/176e228))
- Throw not implemented error from stores ([4bc6c33](https://github.com/modos189/publish-browser-extension/commit/4bc6c33))
- Simplify `tsc` executable path ([4712926](https://github.com/modos189/publish-browser-extension/commit/4712926))
- Use `gulp` & `esbuild` instead of `vite` ([edbe837](https://github.com/modos189/publish-browser-extension/commit/edbe837))
- Pull api utils out of chrome web store ([9aaffa4](https://github.com/modos189/publish-browser-extension/commit/9aaffa4))
- Don't use ESModules so node can execute the CLI ([b31d559](https://github.com/modos189/publish-browser-extension/commit/b31d559))
- Update `package.json` for publishing ([c5d3456](https://github.com/modos189/publish-browser-extension/commit/c5d3456))
- **release:** V1.0.0 [skip ci] ([ed8ab0a](https://github.com/modos189/publish-browser-extension/commit/ed8ab0a))
- Move version to top of package.json ([7701c69](https://github.com/modos189/publish-browser-extension/commit/7701c69))
- Rename `Result` to `Results` ([4a3ad91](https://github.com/modos189/publish-browser-extension/commit/4a3ad91))
- Add repo links to package ([1281abf](https://github.com/modos189/publish-browser-extension/commit/1281abf))
- **release:** V1.0.1 [skip ci] ([c3448dc](https://github.com/modos189/publish-browser-extension/commit/c3448dc))
- Move dev dependency ([dc9d491](https://github.com/modos189/publish-browser-extension/commit/dc9d491))
- Updated package lockfile ([7fb4a9c](https://github.com/modos189/publish-browser-extension/commit/7fb4a9c))
- Fix type error ([0bd29b9](https://github.com/modos189/publish-browser-extension/commit/0bd29b9))
- **release:** V1.1.0 [skip ci] ([02da9f6](https://github.com/modos189/publish-browser-extension/commit/02da9f6))
- **release:** V1.1.1 [skip ci] ([6c71fa9](https://github.com/modos189/publish-browser-extension/commit/6c71fa9))
- **release:** V1.1.2 [skip ci] ([8cfc61a](https://github.com/modos189/publish-browser-extension/commit/8cfc61a))
- **release:** V1.1.3 [skip ci] ([1fb3e58](https://github.com/modos189/publish-browser-extension/commit/1fb3e58))
- **release:** V1.1.4 [skip ci] ([d43e9dd](https://github.com/modos189/publish-browser-extension/commit/d43e9dd))
- Update dependencies and build processes ([#5](https://github.com/modos189/publish-browser-extension/pull/5))
- Improve help command output ([9243a06](https://github.com/modos189/publish-browser-extension/commit/9243a06))
- **release:** V1.2.0 [skip ci] ([2955c71](https://github.com/modos189/publish-browser-extension/commit/2955c71))
- Fix bug with test extension version generation ([3085503](https://github.com/modos189/publish-browser-extension/commit/3085503))
- Fix invalid test extension version ([5338668](https://github.com/modos189/publish-browser-extension/commit/5338668))
- Fix invalid test extension version ([1e8ab0f](https://github.com/modos189/publish-browser-extension/commit/1e8ab0f))
- **release:** V1.3.0 [skip ci] ([394c169](https://github.com/modos189/publish-browser-extension/commit/394c169))
- Fix build output ([1158fe0](https://github.com/modos189/publish-browser-extension/commit/1158fe0))
- **release:** V1.4.0 [skip ci] ([114ea2b](https://github.com/modos189/publish-browser-extension/commit/114ea2b))
- **release:** V1.4.1 [skip ci] ([cb9a088](https://github.com/modos189/publish-browser-extension/commit/cb9a088))
- **release:** V2.0.0 ([337244d](https://github.com/modos189/publish-browser-extension/commit/337244d))
- **release:** V2.1.0 ([99cd583](https://github.com/modos189/publish-browser-extension/commit/99cd583))
- **release:** V2.1.1 ([42041ef](https://github.com/modos189/publish-browser-extension/commit/42041ef))
- **release:** V2.1.2 ([3723396](https://github.com/modos189/publish-browser-extension/commit/3723396))
- **release:** V2.1.3 ([dbdd0d2](https://github.com/modos189/publish-browser-extension/commit/dbdd0d2))

### 🤖 CI

- Add publish workflow ([9750e91](https://github.com/modos189/publish-browser-extension/commit/9750e91))
- Add install step to publish job ([d935d9b](https://github.com/modos189/publish-browser-extension/commit/d935d9b))
- Add verify workflow ([d301f8f](https://github.com/modos189/publish-browser-extension/commit/d301f8f))
- Run E2E test on all branches ([e39988a](https://github.com/modos189/publish-browser-extension/commit/e39988a))
- Pass env vars to verify workflow during publishing ([8433c12](https://github.com/modos189/publish-browser-extension/commit/8433c12))
- Fix publish script ([a5ca302](https://github.com/modos189/publish-browser-extension/commit/a5ca302))
- Standardize github actions with my other repos ([795cb05](https://github.com/modos189/publish-browser-extension/commit/795cb05))
- Fix release environment variables ([6572f61](https://github.com/modos189/publish-browser-extension/commit/6572f61))
- Fix release setup ([407de24](https://github.com/modos189/publish-browser-extension/commit/407de24))

#### ⚠️ Breaking Changes

- ⚠️ Refactor CLI to add `init` command ([#13](https://github.com/modos189/publish-browser-extension/pull/13))

### ❤️ Contributors

- Uncenter ([@uncenter](http://github.com/uncenter))
- Stephen Zhou ([@hyoban](http://github.com/hyoban))
- GitHub Actions
- Aaron Klinker
- Conventional Changelog Action <conventional.changelog.action@github.com>
- Aaron
- Stian Myklebostad

## v2.1.3

[compare changes](https://github.com/aklinker1/publish-browser-extension/compare/v2.1.2...v2.1.3)

### 🩹 Fixes

- Include cli in export paths ([42c356a](https://github.com/aklinker1/publish-browser-extension/commit/42c356a))

## v2.1.2

[compare changes](https://github.com/aklinker1/publish-browser-extension/compare/v2.1.1...v2.1.2)

### 🩹 Fixes

- Support node 20 in `engines` field in `package.json` ([#17](https://github.com/aklinker1/publish-browser-extension/pull/17))

## v2.1.1

[compare changes](https://github.com/aklinker1/publish-browser-extension/compare/v2.1.0...v2.1.1)

### 🩹 Fixes

- Remove log ([d0a4723](https://github.com/aklinker1/publish-browser-extension/commit/d0a4723))
- Don't require all config to run `init` command ([89bfe5d](https://github.com/aklinker1/publish-browser-extension/commit/89bfe5d))

## v2.1.0

[compare changes](https://github.com/aklinker1/publish-browser-extension/compare/v2.0.0...v2.1.0)

### 🚀 Enhancements

- Read variables from `.env.submit` automatically ([#15](https://github.com/aklinker1/publish-browser-extension/pull/15))

## v2.0.0

[compare changes](https://github.com/aklinker1/publish-browser-extension/compare/v1.4.1...v2.0.0)

### 🚀 Enhancements

- ⚠️ Refactor CLI to add `init` command ([#13](https://github.com/aklinker1/publish-browser-extension/pull/13))

### 📖 Documentation

- Add env section to README ([ff62b9b](https://github.com/aklinker1/publish-browser-extension/commit/ff62b9b))

### 🤖 CI

- Standardize github actions with my other repos ([795cb05](https://github.com/aklinker1/publish-browser-extension/commit/795cb05))
- Fix release environment variables ([6572f61](https://github.com/aklinker1/publish-browser-extension/commit/6572f61))
- Fix release setup ([407de24](https://github.com/aklinker1/publish-browser-extension/commit/407de24))

#### ⚠️ Breaking Changes

- ⚠️ Refactor CLI to add `init` command ([#13](https://github.com/aklinker1/publish-browser-extension/pull/13))

### ❤️ Contributors

- Aaron Klinker
