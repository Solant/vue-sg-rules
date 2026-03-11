# vue-sg-rules

This is my collection of ast-grep rules for Vue.js projects. Also contains general linting rules for JavaScript and some package-specific rules.

## Usage

Clone this repo to any folder

```bash
git clone https://github.com/Solant/vue-sg-rules
```

Run `ast-grep` in the root folder of your project

```bash
ast-grep scan -c path/to/vue-sg-rules/sgconfig.yml
```

If you want to reuse some of these rules in your own project, scaffold your own [ast-grep project](https://ast-grep.github.io/guide/project/project-config.html) and copy any of these rules.
