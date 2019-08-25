# Embark Cookiecutter Templates

## Getting Started

### Package Templates

* `embark-javascript-package` is a pure JavaScript package template.

### macOS

```sh
$ brew install cookiecutter
```

### Windows

Follow directions on the [documentation](https://cookiecutter.readthedocs.io/en/latest/installation.html#windows).

## Generating from a template

```
$ cookiecutter embark-javascript-package/ -o ~/src/github.com/embark-framework/embark/packages
project_name [Package scaffold]: Mocha Test Runner
repo_name [embark-mocha-test-runner]:
test_name [mocha_test_runner]:

$ tree ~/src/github.com/embark-framework/embark/packages/embark-mocha-test-runner
~/src/github.com/embark-framework/embark/packages/embark-mocha-test-runner
├── README.md
├── package.json
└── src
    ├── lib
    │   └── index.js
    └── test
        └── mocha_test_runner_test.js

3 directories, 4 files
```
