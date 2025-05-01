# Changelog

## v8.0.2

[compare changes](https://github.com/kikiutils/node-shared/compare/v8.0.1...v8.0.2)

### 💅 Refactors

- Replace all import * as and default imports with named imports in test files ([7fc3210](https://github.com/kikiutils/node-shared/commit/7fc3210))
- Remove redundant type assertions ([ddf011c](https://github.com/kikiutils/node-shared/commit/ddf011c))
- Replace if-else chain with switch in `getDateRangeFromDate` ([72ba2e2](https://github.com/kikiutils/node-shared/commit/72ba2e2))

### 📖 Documentation

- Update README ([1704ec7](https://github.com/kikiutils/node-shared/commit/1704ec7))

### 🏡 Chore

- Format script ([16ca049](https://github.com/kikiutils/node-shared/commit/16ca049))
- Update file permissions after installing or updating dependencies ([d141f76](https://github.com/kikiutils/node-shared/commit/d141f76))
- Add `--hideAuthorEmail` flag to bumplog command ([382091b](https://github.com/kikiutils/node-shared/commit/382091b))
- Add typecheck command to package.json scripts ([2a1f7e0](https://github.com/kikiutils/node-shared/commit/2a1f7e0))
- Rename `jest.config.js` to `jest.config.mjs` ([76371a1](https://github.com/kikiutils/node-shared/commit/76371a1))
- Reorder lint, test, and build steps in release command ([b63dcb4](https://github.com/kikiutils/node-shared/commit/b63dcb4))
- Disable `isolatedDeclarations` in tsconfig ([ed1636f](https://github.com/kikiutils/node-shared/commit/ed1636f))
- Update `modify-files-permissions.sh` ([89f72e3](https://github.com/kikiutils/node-shared/commit/89f72e3))

### ✅ Tests

- Add pass test unit ([d7b98bd](https://github.com/kikiutils/node-shared/commit/d7b98bd))
- Update datetime `getDateRangeFromDate` test unit ([f16130e](https://github.com/kikiutils/node-shared/commit/f16130e))

### 🤖 CI

- Add test github workflow config file ([dd421d1](https://github.com/kikiutils/node-shared/commit/dd421d1))

### ❤️ Contributors

- kiki-kanri

## v8.0.1

[compare changes](https://github.com/kikiutils/node-shared/compare/v8.0.0...v8.0.1)

### 🏡 Chore

- Set `sideEffects` to false in package.json ([331c0d8](https://github.com/kikiutils/node-shared/commit/331c0d8))

### ❤️ Contributors

- kiki-kanri

## v8.0.0

[compare changes](https://github.com/kikiutils/node-shared/compare/v7.1.0...v8.0.0)

### 💅 Refactors

- ⚠️ Remove all default export ([a6d6a54](https://github.com/kikiutils/node-shared/commit/a6d6a54))
- Update import style for some modules ([fa9947e](https://github.com/kikiutils/node-shared/commit/fa9947e))

### 🏡 Chore

- Upgrade dependencies ([bebb21b](https://github.com/kikiutils/node-shared/commit/bebb21b))

#### ⚠️ Breaking Changes

- ⚠️ Remove all default export ([a6d6a54](https://github.com/kikiutils/node-shared/commit/a6d6a54))

### ❤️ Contributors

- kiki-kanri

## v7.1.0

[compare changes](https://github.com/kikiutils/node-shared/compare/v7.0.0...v7.1.0)

### 🚀 Enhancements

- Add `generateWithNestedRandomLength` utils and test unit ([39cd4eb](https://github.com/kikiutils/node-shared/commit/39cd4eb))

### ❤️ Contributors

- kiki-kanri

## v7.0.0

[compare changes](https://github.com/kikiutils/node-shared/compare/v6.0.1...v7.0.0)

### 🚀 Enhancements

- ⚠️ Remove `randomAlphabeticString` and `randomLowerCaseAlphabeticString`, then add `randomString` utils ([fe87907](https://github.com/kikiutils/node-shared/commit/fe87907))

### 💅 Refactors

- ⚠️ Rename `flattenToSingleValue` to `extractFirstValue` ([cd5ad41](https://github.com/kikiutils/node-shared/commit/cd5ad41))
- ⚠️ Rename `formatDateOrTimestamp` to `formatDate` ([089b408](https://github.com/kikiutils/node-shared/commit/089b408))
- Remove unnecessary `as string` in `checkAndGetEnvValue` ([7430a1c](https://github.com/kikiutils/node-shared/commit/7430a1c))
- ⚠️ Rename `calculateToPercentageString` to `toPercentageString` ([cf37e26](https://github.com/kikiutils/node-shared/commit/cf37e26))
- ⚠️ Rename `prettyNumberToString` to `toCompactNumberString` ([d4730fa](https://github.com/kikiutils/node-shared/commit/d4730fa))
- Remove default value for `randomString` length and add validation ([817b00f](https://github.com/kikiutils/node-shared/commit/817b00f))
- Move `extractFirstValue` to `general` file ([343ee68](https://github.com/kikiutils/node-shared/commit/343ee68))

### 📖 Documentation

- Update and clean up all function comments ([79881cf](https://github.com/kikiutils/node-shared/commit/79881cf))
- Update README and package description ([eba6bf2](https://github.com/kikiutils/node-shared/commit/eba6bf2))

### 🏡 Chore

- ⚠️ Remove `useHonoLogger` lib ([24e39a2](https://github.com/kikiutils/node-shared/commit/24e39a2))
- ⚠️ Remove `setReadonlyConstantToGlobalThis` utils ([6ff6cb9](https://github.com/kikiutils/node-shared/commit/6ff6cb9))
- ⚠️ Remove `axios` utils ([756fd3e](https://github.com/kikiutils/node-shared/commit/756fd3e))
- Format code ([4a808da](https://github.com/kikiutils/node-shared/commit/4a808da))
- Upgrade dependencies ([8beaf82](https://github.com/kikiutils/node-shared/commit/8beaf82))
- Set `hideAuthorEmail` arg in changelogen command ([1ab74e2](https://github.com/kikiutils/node-shared/commit/1ab74e2))
- Remove unused dependencies and clean up package description and keywords ([624596a](https://github.com/kikiutils/node-shared/commit/624596a))
- Format and lint code ([fd22a1f](https://github.com/kikiutils/node-shared/commit/fd22a1f))
- Remove `tslib` devDependencies ([4132f47](https://github.com/kikiutils/node-shared/commit/4132f47))

### ✅ Tests

- Update unit tests ([23c1d3e](https://github.com/kikiutils/node-shared/commit/23c1d3e))

#### ⚠️ Breaking Changes

- ⚠️ Remove `randomAlphabeticString` and `randomLowerCaseAlphabeticString`, then add `randomString` utils ([fe87907](https://github.com/kikiutils/node-shared/commit/fe87907))
- ⚠️ Rename `flattenToSingleValue` to `extractFirstValue` ([cd5ad41](https://github.com/kikiutils/node-shared/commit/cd5ad41))
- ⚠️ Rename `formatDateOrTimestamp` to `formatDate` ([089b408](https://github.com/kikiutils/node-shared/commit/089b408))
- ⚠️ Rename `calculateToPercentageString` to `toPercentageString` ([cf37e26](https://github.com/kikiutils/node-shared/commit/cf37e26))
- ⚠️ Rename `prettyNumberToString` to `toCompactNumberString` ([d4730fa](https://github.com/kikiutils/node-shared/commit/d4730fa))
- ⚠️ Remove `useHonoLogger` lib ([24e39a2](https://github.com/kikiutils/node-shared/commit/24e39a2))
- ⚠️ Remove `setReadonlyConstantToGlobalThis` utils ([6ff6cb9](https://github.com/kikiutils/node-shared/commit/6ff6cb9))
- ⚠️ Remove `axios` utils ([756fd3e](https://github.com/kikiutils/node-shared/commit/756fd3e))

### ❤️ Contributors

- kiki-kanri

## v6.0.1

[compare changes](https://github.com/kikiutils/node-shared/compare/v6.0.0...v6.0.1)

### 🏡 Chore

- Update repository URL ([136c508](https://github.com/kikiutils/node-shared/commit/136c508))
- Upgrade dependencies ([071b573](https://github.com/kikiutils/node-shared/commit/071b573))

### ❤️ Contributors

- kiki-kanri

## v6.0.0

[compare changes](https://github.com/kikiutils/node-shared/compare/v5.1.5...v6.0.0)

### 💅 Refactors

- ⚠️ Enforce camelCase naming for all variables, classes, methods, types, etc., ignoring abbreviations ([847b125](https://github.com/kikiutils/node-shared/commit/847b125))

### 🏡 Chore

- Upgrade dependencies and add `pnpm.onlyBuiltDependencies` setting to package.json ([bf9ca52](https://github.com/kikiutils/node-shared/commit/bf9ca52))

#### ⚠️ Breaking Changes

- ⚠️ Enforce camelCase naming for all variables, classes, methods, types, etc., ignoring abbreviations ([847b125](https://github.com/kikiutils/node-shared/commit/847b125))

### ❤️ Contributors

- kiki-kanri

## v5.1.5

[compare changes](https://github.com/kikiutils/node-shared/compare/v5.1.4...v5.1.5)

### 📦 Build

- Enable sourcemap output in build process ([379ba75](https://github.com/kikiutils/node-shared/commit/379ba75))

### 🏡 Chore

- Upgrade dependencies ([d0943fa](https://github.com/kikiutils/node-shared/commit/d0943fa))
- Modify pack file structure and update package.json.exports configuration ([4429859](https://github.com/kikiutils/node-shared/commit/4429859))

### ❤️ Contributors

- kiki-kanri

## v5.1.4

[compare changes](https://github.com/kikiutils/node-shared/compare/v5.1.3...v5.1.4)

### 💅 Refactors

- Change Url to URL ([844051b](https://github.com/kikiutils/node-shared/commit/844051b))
- Remove process import statement ([0209f3c](https://github.com/kikiutils/node-shared/commit/0209f3c))

### 🏡 Chore

- Upgrade dependencies ([125646f](https://github.com/kikiutils/node-shared/commit/125646f))
- Upgrade dependencies ([bfafc04](https://github.com/kikiutils/node-shared/commit/bfafc04))

### 🎨 Styles

- Format and lint all files ([8670067](https://github.com/kikiutils/node-shared/commit/8670067))

### ❤️ Contributors

- kiki-kanri

## v5.1.3

[compare changes](https://github.com/kikiutils/node-shared/compare/v5.1.2...v5.1.3)

### 🩹 Fixes

- Resolve logger issue in browser due to process.env import method ([5622de5](https://github.com/kikiutils/node-shared/commit/5622de5))

### 🏡 Chore

- Upgrade dependencies ([71e77cd](https://github.com/kikiutils/node-shared/commit/71e77cd))

### 🎨 Styles

- Format and lint codes ([62902ed](https://github.com/kikiutils/node-shared/commit/62902ed))

### ❤️ Contributors

- kiki-kanri

## v5.1.2

[compare changes](https://github.com/kikiutils/node-shared/compare/v5.1.1...v5.1.2)

### 💅 Refactors

- Simplify wrapper functions by removing async/await ([09af6a0](https://github.com/kikiutils/node-shared/commit/09af6a0))

### 🏡 Chore

- Replace Prettier with ESLint, add related files, and update VSCode settings ([ab526fe](https://github.com/kikiutils/node-shared/commit/ab526fe))
- Modify scripts in package.json ([0bd0a63](https://github.com/kikiutils/node-shared/commit/0bd0a63))
- Update eslint-config and format codes ([e56c18c](https://github.com/kikiutils/node-shared/commit/e56c18c))
- Upgrade dependencies ([38923a3](https://github.com/kikiutils/node-shared/commit/38923a3))

### 🎨 Styles

- Format and lint all files ([9ec40d6](https://github.com/kikiutils/node-shared/commit/9ec40d6))
- Change all indentation to 4 spaces ([f65d19a](https://github.com/kikiutils/node-shared/commit/f65d19a))

### ❤️ Contributors

- kiki-kanri

## v5.1.1

[compare changes](https://github.com/kikiutils/node-shared/compare/v5.1.0...v5.1.1)

### 🏡 Chore

- Upgrade dependencies ([57c452c](https://github.com/kikiutils/node-shared/commit/57c452c))
- Add `tslib` to devDependencies ([f93d4cc](https://github.com/kikiutils/node-shared/commit/f93d4cc))

### ❤️ Contributors

- kiki-kanri

## v5.1.0

[compare changes](https://github.com/kikiutils/node-shared/compare/v5.0.1...v5.1.0)

### 🚀 Enhancements

- Set value parameter type of setReadonlyConstantToGlobalThis as generic ([cbcf336](https://github.com/kikiutils/node-shared/commit/cbcf336))

### 🏡 Chore

- Update minimum Node.js version and version list in CI file ([d5d261a](https://github.com/kikiutils/node-shared/commit/d5d261a))
- Upgrade dependencies ([1f4659f](https://github.com/kikiutils/node-shared/commit/1f4659f))

### ❤️ Contributors

- kiki-kanri

## v5.0.1

[compare changes](https://github.com/kikiutils/node-shared/compare/v5.0.0...v5.0.1)

### 📖 Documentation

- Add codecov badge to README ([b19566b](https://github.com/kikiutils/node-shared/commit/b19566b))

### 🏡 Chore

- Upgrade dependencies and remove tslib ([7923643](https://github.com/kikiutils/node-shared/commit/7923643))
- Modify tsconfig.json ([754d072](https://github.com/kikiutils/node-shared/commit/754d072))
- Upgrade dependencies and modify release script ([de51810](https://github.com/kikiutils/node-shared/commit/de51810))

### ✅ Tests

- Set timezone to UTC during tests ([637c47a](https://github.com/kikiutils/node-shared/commit/637c47a))
- Update datetime unit tests ([b2987e0](https://github.com/kikiutils/node-shared/commit/b2987e0))
- Add unit tests for number.ts and string.ts ([4ad7142](https://github.com/kikiutils/node-shared/commit/4ad7142))

### 🤖 CI

- Add new test CI configuration file ([84450b3](https://github.com/kikiutils/node-shared/commit/84450b3))

### ❤️ Contributors

- kiki-kanri

## v5.0.0

[compare changes](https://github.com/kikiutils/node-shared/compare/v4.4.0...v5.0.0)

### Migration Notes

- Changed the "Sha" abbreviation in `cryptoMD5` related functions to uppercase ("SHA").
- The package will no longer install accompanying dependencies automatically. If you need to use related functionalities, you must manually install the corresponding dependencies.

### 🚀 Enhancements

- Add release script to package.json ([4541063](https://github.com/kikiutils/node-shared/commit/4541063))

### 🩹 Fixes

- Resolve issue with unquoted glob path in build script for specified imports ([4831bb6](https://github.com/kikiutils/node-shared/commit/4831bb6))

### 💅 Refactors

- ⚠️ Merge functions from object.ts into index.ts ([da29903](https://github.com/kikiutils/node-shared/commit/da29903))
- ⚠️ Change function shorthand names in crypto-hash.ts ([64dad0d](https://github.com/kikiutils/node-shared/commit/64dad0d))

### 📖 Documentation

- Update README ([c297a79](https://github.com/kikiutils/node-shared/commit/c297a79))

### 🏡 Chore

- Switch changelog generation package and upgrade dependencies ([a47afd6](https://github.com/kikiutils/node-shared/commit/a47afd6))
- ⚠️ Change all dependencies to devDependencies ([9f92be7](https://github.com/kikiutils/node-shared/commit/9f92be7))
- Update release script ([b13bdcd](https://github.com/kikiutils/node-shared/commit/b13bdcd))

### ✅ Tests

- Add unit tests for `setReadonlyConstantToGlobalThis` ([aafe978](https://github.com/kikiutils/node-shared/commit/aafe978))
- Modify unit tests ([ec85e0c](https://github.com/kikiutils/node-shared/commit/ec85e0c))

#### ⚠️ Breaking Changes

- ⚠️ Merge functions from object.ts into index.ts ([da29903](https://github.com/kikiutils/node-shared/commit/da29903))
- ⚠️ Change function shorthand names in crypto-hash.ts ([64dad0d](https://github.com/kikiutils/node-shared/commit/64dad0d))
- ⚠️ Change all dependencies to devDependencies ([9f92be7](https://github.com/kikiutils/node-shared/commit/9f92be7))

### ❤️ Contributors

- kiki-kanri

## v4.4.0

[compare changes](https://github.com/kikiutils/node-shared/compare/v4.3.1...v4.4.0)

### 🚀 Enhancements

- Add `setReadonlyConstantToGlobalThis` function ([115c6b7](https://github.com/kikiutils/node-shared/commit/115c6b7))

### 🏡 Chore

- Upgrade dependencies ([7fdda21](https://github.com/kikiutils/node-shared/commit/7fdda21))

### ❤️ Contributors

- kiki-kanri

## v4.3.1

[compare changes](https://github.com/kikiutils/node-shared/compare/v4.3.0...v4.3.1)

### 🩹 Fixes

- **hono:** Resolve issue with logger message handling ([bdb8d4d](https://github.com/kikiutils/node-shared/commit/bdb8d4d))

### ❤️ Contributors

- kiki-kanri

## v4.3.0

[compare changes](https://github.com/kikiutils/node-shared/compare/v4.2.4...v4.3.0)

### 🚀 Enhancements

- Add `flattenToSingleValue` function ([89077cb](https://github.com/kikiutils/node-shared/commit/89077cb))

### 🏡 Chore

- Update script ([ca98dac](https://github.com/kikiutils/node-shared/commit/ca98dac))
- Upgrade dependencies ([4a3ac53](https://github.com/kikiutils/node-shared/commit/4a3ac53))
- Add index export to package.json exports ([e017218](https://github.com/kikiutils/node-shared/commit/e017218))
- Add tslib to devDependencies ([08fffce](https://github.com/kikiutils/node-shared/commit/08fffce))

### ✅ Tests

- Add unit tests for `flattenToSingleValue` function ([338c475](https://github.com/kikiutils/node-shared/commit/338c475))

### ❤️ Contributors

- kiki-kanri

## v4.2.4

[compare changes](https://github.com/kikiutils/node-shared/compare/v4.2.3...v4.2.4)

### 🏡 Chore

- Upgrade dependencies ([59f187b](https://github.com/kikiutils/node-shared/commit/59f187b))

### ❤️ Contributors

- kiki-kanri

## v4.2.3

[compare changes](https://github.com/kikiutils/node-shared/compare/v4.2.2...v4.2.3)

### 🩹 Fixes

- Handle mixed number and string enum values in `getEnumStringValues` ([57b6ae9](https://github.com/kikiutils/node-shared/commit/57b6ae9))

### 🏡 Chore

- Upgrade dependencies ([ba15c66](https://github.com/kikiutils/node-shared/commit/ba15c66))
- Add jest dependency and related files ([49f84e4](https://github.com/kikiutils/node-shared/commit/49f84e4))

### ✅ Tests

- Add test cases ([86ca8db](https://github.com/kikiutils/node-shared/commit/86ca8db))

### ❤️ Contributors

- kiki-kanri

## v4.2.2

[compare changes](https://github.com/kikiutils/node-shared/compare/v4.2.1...v4.2.2)

### 🩹 Fixes

- Prevent default value handling from overwriting non-null/undefined falsy values ([a7b9c6e](https://github.com/kikiutils/node-shared/commit/a7b9c6e))

### 🏡 Chore

- Upgrade dependencies ([4185969](https://github.com/kikiutils/node-shared/commit/4185969))

### ❤️ Contributors

- kiki-kanri

## v4.2.1

[compare changes](https://github.com/kikiutils/node-shared/compare/v4.2.0...v4.2.1)

### 🩹 Fixes

- Correct options property name in getDateRangeFromDate ([e48375c](https://github.com/kikiutils/node-shared/commit/e48375c))

### ❤️ Contributors

- kiki-kanri

## v4.2.0

[compare changes](https://github.com/kikiutils/node-shared/compare/v4.1.0...v4.2.0)

### 🚀 Enhancements

- Add `getDateRangeFromDate` function ([cf9d212](https://github.com/kikiutils/node-shared/commit/cf9d212))

### 📖 Documentation

- Update README ([8419a5e](https://github.com/kikiutils/node-shared/commit/8419a5e))

### 🏡 Chore

- Remove rollup files and dependencies and switch to builder build ([1aca08a](https://github.com/kikiutils/node-shared/commit/1aca08a))
- Upgrade dependencies ([37ecc2e](https://github.com/kikiutils/node-shared/commit/37ecc2e))

### ❤️ Contributors

- kiki-kanri

## v4.1.0

[compare changes](https://github.com/kikiutils/node-shared/compare/v4.0.0...v4.1.0)

### 🚀 Enhancements

- Add named exports to consola and pino files ([131a03c](https://github.com/kikiutils/node-shared/commit/131a03c))

### ❤️ Contributors

- kiki-kanri

## v4.0.0

[compare changes](https://github.com/kikiutils/node-shared/compare/v3.1.0...v4.0.0)

### 🚀 Enhancements

- Add consola logger and related files ([c2fb81c](https://github.com/kikiutils/node-shared/commit/c2fb81c))

### 💅 Refactors

- ⚠️ Rename request.ts to axios.ts ([f9179fd](https://github.com/kikiutils/node-shared/commit/f9179fd))
- ⚠️ Rename logger.ts to pino.ts ([2d3ec0e](https://github.com/kikiutils/node-shared/commit/2d3ec0e))

### 📖 Documentation

- Update comments for pino logger ([897570b](https://github.com/kikiutils/node-shared/commit/897570b))
- Update README and package.json ([b8025db](https://github.com/kikiutils/node-shared/commit/b8025db))

### 🏡 Chore

- Upgrade dependencies ([e8209f4](https://github.com/kikiutils/node-shared/commit/e8209f4))
- Remove type field from package.json ([ed68274](https://github.com/kikiutils/node-shared/commit/ed68274))
- Update rollup.config.ts and tsconfig.json ([f366dda](https://github.com/kikiutils/node-shared/commit/f366dda))
- ⚠️ Remove object.ts file ([9068d40](https://github.com/kikiutils/node-shared/commit/9068d40))

#### ⚠️ Breaking Changes

- ⚠️ Rename request.ts to axios.ts ([f9179fd](https://github.com/kikiutils/node-shared/commit/f9179fd))
- ⚠️ Rename logger.ts to pino.ts ([2d3ec0e](https://github.com/kikiutils/node-shared/commit/2d3ec0e))
- ⚠️ Remove object.ts file ([9068d40](https://github.com/kikiutils/node-shared/commit/9068d40))

### ❤️ Contributors

- kiki-kanri

## v3.1.0

[compare changes](https://github.com/kikiutils/node-shared/compare/v3.0.1...v3.1.0)

### 🚀 Enhancements

- Add `cryptoMd5` and `cryptoMd5ToBuffer` functions ([10458b1](https://github.com/kikiutils/node-shared/commit/10458b1))

### 📖 Documentation

- Update README and keywords in package.json ([9d144eb](https://github.com/kikiutils/node-shared/commit/9d144eb))

### 🏡 Chore

- Update Rollup config ([195f323](https://github.com/kikiutils/node-shared/commit/195f323))

### ❤️ Contributors

- kiki-kanri

## v3.0.1

[compare changes](https://github.com/kikiutils/node-shared/compare/v3.0.0...v3.0.1)

### 🏡 Chore

- Update Rollup config ([f516126](https://github.com/kikiutils/node-shared/commit/f516126))

### ❤️ Contributors

- kiki-kanri

## v3.0.0

[compare changes](https://github.com/kikiutils/node-shared/compare/v2.0.0...v3.0.0)

### 💅 Refactors

- ⚠️ Remove named exports in logger file ([0a01d4a](https://github.com/kikiutils/node-shared/commit/0a01d4a))

### 📖 Documentation

- Update README and description in package.json ([8a24ff0](https://github.com/kikiutils/node-shared/commit/8a24ff0))

### 📦 Build

- Switch build process to Rollup ([0869dee](https://github.com/kikiutils/node-shared/commit/0869dee))

### 🏡 Chore

- Update .gitignore ([a5a97e4](https://github.com/kikiutils/node-shared/commit/a5a97e4))
- Upgrade dependencies ([ccf5f5c](https://github.com/kikiutils/node-shared/commit/ccf5f5c))
- Update exports in package.json ([d147783](https://github.com/kikiutils/node-shared/commit/d147783))

#### ⚠️ Breaking Changes

- ⚠️ Remove named exports in logger file ([0a01d4a](https://github.com/kikiutils/node-shared/commit/0a01d4a))

### ❤️ Contributors

- kiki-kanri

## v2.0.0

[compare changes](https://github.com/kikiutils/node-shared/compare/v2.0.0-rc.4...v2.0.0)

### 🚀 Enhancements

- Add ksort function ([0f6571e](https://github.com/kikiutils/node-shared/commit/0f6571e))
- **number:** Add options parameter to `prettyNumberToString` function ([fd7374d](https://github.com/kikiutils/node-shared/commit/fd7374d))
- **hono:** Add generic type parameter to `useHonoLogger` function ([43a355b](https://github.com/kikiutils/node-shared/commit/43a355b))

### 💅 Refactors

- **number:** ⚠️ Rename `toPercentString` to `calculateToPercentageString` and rewrite calculations using decimal.js ([17a4053](https://github.com/kikiutils/node-shared/commit/17a4053))
- ⚠️ Move calculateToPercentageString to math.ts file ([e1686c2](https://github.com/kikiutils/node-shared/commit/e1686c2))

### 📖 Documentation

- Add comments and examples ([3e72bec](https://github.com/kikiutils/node-shared/commit/3e72bec))
- Update README and modify description field in package.json ([fcec53e](https://github.com/kikiutils/node-shared/commit/fcec53e))

### 🏡 Chore

- Upgrade dependencies ([646da01](https://github.com/kikiutils/node-shared/commit/646da01))

#### ⚠️ Breaking Changes

- **number:** ⚠️ Rename `toPercentString` to `calculateToPercentageString` and rewrite calculations using decimal.js ([17a4053](https://github.com/kikiutils/node-shared/commit/17a4053))
- ⚠️ Move calculateToPercentageString to math.ts file ([e1686c2](https://github.com/kikiutils/node-shared/commit/e1686c2))

### ❤️ Contributors

- kiki-kanri

## v2.0.0-rc.4

[compare changes](https://github.com/kikiutils/node-shared/compare/v2.0.0-rc.3...v2.0.0-rc.4)

### 🚀 Enhancements

- Add functions for SHA3 hashing with crypto ([089fc8e](https://github.com/kikiutils/node-shared/commit/089fc8e))
- Add Uint8Array as an input type for SHA3 related functions ([350907c](https://github.com/kikiutils/node-shared/commit/350907c))

### 🩹 Fixes

- Correct return type error in enum utils ([0ae2262](https://github.com/kikiutils/node-shared/commit/0ae2262))

### 🏡 Chore

- Upgrade dependencies ([49999da](https://github.com/kikiutils/node-shared/commit/49999da))

### ❤️ Contributors

- kiki-kanri

## v2.0.0-rc.3

[compare changes](https://github.com/kikiutils/node-shared/compare/v2.0.0-rc.2...v2.0.0-rc.3)

### 💅 Refactors

- Modify build and packaging process ([a248c8f](https://github.com/kikiutils/node-shared/commit/a248c8f))

### ❤️ Contributors

- kiki-kanri

## v2.0.0-rc.2

[compare changes](https://github.com/kikiutils/node-shared/compare/v2.0.0-rc.1...v2.0.0-rc.2)

### 🚀 Enhancements

- Add enum utils ([8c6f177](https://github.com/kikiutils/node-shared/commit/8c6f177))

### 🏡 Chore

- Upgrade dependencies ([8a10efb](https://github.com/kikiutils/node-shared/commit/8a10efb))

### ❤️ Contributors

- kiki-kanri

## v2.0.0-rc.1

[compare changes](https://github.com/kikiutils/node-shared/compare/v2.0.0-rc.0...v2.0.0-rc.1)

### 🚀 Enhancements

- Add `useHonoLogger` utils ([7e7e829](https://github.com/kikiutils/node-shared/commit/7e7e829))

### 💅 Refactors

- Modify build and packaging process ([6253743](https://github.com/kikiutils/node-shared/commit/6253743))

### ❤️ Contributors

- kiki-kanri

## v2.0.0-rc.0

[compare changes](https://github.com/kikiutils/node-shared/compare/v2.0.0-alpha.3...v2.0.0-rc.0)

### 🚀 Enhancements

- Copy README into dist folder during build ([bbefce5](https://github.com/kikiutils/node-shared/commit/bbefce5))
- Set pino logger level using env value ([23185fd](https://github.com/kikiutils/node-shared/commit/23185fd))

### 📖 Documentation

- Edit README ([66912af](https://github.com/kikiutils/node-shared/commit/66912af))

### 🏡 Chore

- Upgrade dependencies ([18bf489](https://github.com/kikiutils/node-shared/commit/18bf489))

### ❤️ Contributors

- kiki-kanri

## v2.0.0-alpha.3

[compare changes](https://github.com/kikiutils/node-shared/compare/v2.0.0-alpha.2...v2.0.0-alpha.3)

### 💅 Refactors

- Switch package to ESM and set 'type' to 'module' in package.json ([66f3ee3](https://github.com/kikiutils/node-shared/commit/66f3ee3))

### 🏡 Chore

- Rename script file and format tsc-multi.json ([dbbb34e](https://github.com/kikiutils/node-shared/commit/dbbb34e))
- Upgrade dependencies ([cdfd392](https://github.com/kikiutils/node-shared/commit/cdfd392))

### ❤️ Contributors

- kiki-kanri

## v2.0.0-alpha.2

[compare changes](https://github.com/kikiutils/node-shared/compare/v2.0.0-alpha.1...v2.0.0-alpha.2)

### 🚀 Enhancements

- Add cjs format to build output files ([3c9edaa](https://github.com/kikiutils/node-shared/commit/3c9edaa))

### 🏡 Chore

- Upgrade dependencies ([467cf12](https://github.com/kikiutils/node-shared/commit/467cf12))

### ❤️ Contributors

- kiki-kanri

## v2.0.0-alpha.1

[compare changes](https://github.com/kikiutils/node-shared/compare/v2.0.0-alpha.0...v2.0.0-alpha.1)

### 🚀 Enhancements

- Add exports configuration to package.json ([832d106](https://github.com/kikiutils/node-shared/commit/832d106))

### ❤️ Contributors

- kiki-kanri

## v2.0.0-alpha.0

[compare changes](https://github.com/kikiutils/node-shared/compare/v1.1.3...v2.0.0-alpha.0)

### BREAKING CHANGES

The module is completely rewritten.

Old features will be changed or removed.

Restricted to nodejs version 18 or above.

### 🚀 Enhancements

- Add files ([e7eca4c](https://github.com/kikiutils/node-shared/commit/e7eca4c))

### 💅 Refactors

- Change build process and set package.json 'type' field to 'module' ([e8a5101](https://github.com/kikiutils/node-shared/commit/e8a5101))

### ❤️ Contributors

- kiki-kanri
