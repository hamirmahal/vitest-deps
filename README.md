```
$  npm install --save-dev vitest

added 44 packages in 981ms

12 packages are looking for funding
  run `npm fund` for details
```

```
$  npm audit
# npm audit report

esbuild  <=0.24.2
Severity: moderate
esbuild enables any website to send any requests to the development server and read the response - https://github.com/advisories/GHSA-67mh-4wv8-2f99
fix available via `npm audit fix --force`
Will install vitest@0.0.28, which is a breaking change
node_modules/esbuild
  vite  0.11.0 - 6.1.1
  Depends on vulnerable versions of esbuild
  node_modules/vite
    @vitest/mocker  *
    Depends on vulnerable versions of vite
    node_modules/@vitest/mocker
      vitest  0.0.1 - 0.0.12 || >=0.0.29
      Depends on vulnerable versions of @vitest/mocker
      Depends on vulnerable versions of vite
      Depends on vulnerable versions of vite-node
      node_modules/vitest
    vite-node  *
    Depends on vulnerable versions of vite
    node_modules/vite-node

5 moderate severity vulnerabilities

To address all issues (including breaking changes), run:
  npm audit fix --force
```

```
$  npm audit fix

up to date, audited 45 packages in 771ms

12 packages are looking for funding
  run `npm fund` for details

# npm audit report

esbuild  <=0.24.2
Severity: moderate
esbuild enables any website to send any requests to the development server and read the response - https://github.com/advisories/GHSA-67mh-4wv8-2f99
fix available via `npm audit fix --force`
Will install vitest@0.0.28, which is a breaking change
node_modules/esbuild
  vite  0.11.0 - 6.1.1
  Depends on vulnerable versions of esbuild
  node_modules/vite
    @vitest/mocker  *
    Depends on vulnerable versions of vite
    node_modules/@vitest/mocker
      vitest  0.0.1 - 0.0.12 || >=0.0.29
      Depends on vulnerable versions of @vitest/mocker
      Depends on vulnerable versions of vite
      Depends on vulnerable versions of vite-node
      node_modules/vitest
    vite-node  *
    Depends on vulnerable versions of vite
    node_modules/vite-node

5 moderate severity vulnerabilities

To address all issues (including breaking changes), run:
  npm audit fix --force
```

```
$  npm view vitest

vitest@3.0.6 | MIT | deps: 20 | versions: 394
Next generation testing framework powered by Vite
https://github.com/vitest-dev/vitest#readme

keywords: vite, vitest, test, jest

bin: vitest

dist
.tarball: https://registry.npmjs.org/vitest/-/vitest-3.0.6.tgz
.shasum: 2fd1571a3cc1fa1648e29af73ff2dc85872f3a69
.integrity: sha512-/iL1Sc5VeDZKPDe58oGK4HUFLhw6b5XdY1MYawjuSaDA4sEfYlY9HnS6aCEG26fX+MgUi7MwlduTBHHAI/OvMA==
.unpackedSize: 1.6 MB

dependencies:
@vitest/expect: 3.0.6         @vitest/snapshot: 3.0.6       debug: ^4.4.0                 std-env: ^3.8.0               tinyrainbow: ^2.0.0
@vitest/mocker: 3.0.6         @vitest/spy: 3.0.6            expect-type: ^1.1.0           tinybench: ^2.9.0             vite-node: 3.0.6
@vitest/pretty-format: ^3.0.6 @vitest/utils: 3.0.6          magic-string: ^0.30.17        tinyexec: ^0.3.2              vite: ^5.0.0 || ^6.0.0
@vitest/runner: 3.0.6         chai: ^5.2.0                  pathe: ^2.0.3                 tinypool: ^1.0.2              why-is-node-running: ^2.3.0

maintainers:
- antfu
- patak
- oreanno
- vitestbot

dist-tags:
beta: 3.0.0-beta.4  latest: 3.0.6

published 3 days ago by vitestbot
```
