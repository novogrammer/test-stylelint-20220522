# test-stylelint-20220522

```
$ npm install
$ npm run stylelint
```


## Error Message

```
$ npm run stylelint

> test-stylelint-20220522@1.0.0 stylelint
> stylelint --formatter verbose --fix 'src/css/**/*.scss'

Error: Expected a pseudo-class or pseudo-element.
    at /Users/novo/Documents/projects/test-stylelint-20220522/src/css/failed.scss:6:3
    at Root._error (/Users/novo/Documents/projects/test-stylelint-20220522/node_modules/postcss-selector-parser/dist/parser.js:174:16)
    at Root.error (/Users/novo/Documents/projects/test-stylelint-20220522/node_modules/postcss-selector-parser/dist/selectors/root.js:43:19)
    at Parser.error (/Users/novo/Documents/projects/test-stylelint-20220522/node_modules/postcss-selector-parser/dist/parser.js:740:21)
    at Parser.expected (/Users/novo/Documents/projects/test-stylelint-20220522/node_modules/postcss-selector-parser/dist/parser.js:1133:19)
    at Parser.pseudo (/Users/novo/Documents/projects/test-stylelint-20220522/node_modules/postcss-selector-parser/dist/parser.js:875:19)
    at Parser.parse (/Users/novo/Documents/projects/test-stylelint-20220522/node_modules/postcss-selector-parser/dist/parser.js:1084:14)
    at Parser.loop (/Users/novo/Documents/projects/test-stylelint-20220522/node_modules/postcss-selector-parser/dist/parser.js:1043:12)
    at new Parser (/Users/novo/Documents/projects/test-stylelint-20220522/node_modules/postcss-selector-parser/dist/parser.js:164:10)
    at Processor._root (/Users/novo/Documents/projects/test-stylelint-20220522/node_modules/postcss-selector-parser/dist/processor.js:53:18)
    at Processor._runSync (/Users/novo/Documents/projects/test-stylelint-20220522/node_modules/postcss-selector-parser/dist/processor.js:100:21)

```