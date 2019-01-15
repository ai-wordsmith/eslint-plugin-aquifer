# eslint-plugin-starts-with-ts-check

ensure that each javascript file starts with &#39;//@ts-check&#39;

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-starts-with-ts-check`:

```
$ npm install eslint-plugin-starts-with-ts-check --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-starts-with-ts-check` globally.

## Usage

Add `starts-with-ts-check` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "starts-with-ts-check"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "starts-with-ts-check/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here



## Resources

https://eslint.org/docs/developer-guide/working-with-rules

https://eslint.org/docs/developer-guide/working-with-rules#runtime-rules - Program vs IfStatement etc

simple example:

https://github.com/lydell/eslint-plugin-simple-import-sort/blob/master/src/sort.js

https://github.com/lydell/eslint-plugin-simple-import-sort/blob/master/test/sort.test.js

https://flexport.engineering/writing-custom-lint-rules-for-your-picky-developers-67732afa1803
