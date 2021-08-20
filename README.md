<a href="https://theorylabs.dev" target="_blank">
 <img src="https://picc.io/GUfS6PH.png" alt="TheoryLabs Logo" style="display:block;margin-left: auto;margin-right: auto;width: 35%;">
</a>

# Common Errors
> **Common Errors**, thier properties _(i.e. `err.name`, `err.code`, etc.)_, methods, classed counter-parts _(i.e `TypeError`, `AggregateError`, etc.)_ and more in a Human-Readable format. Essentially provides an importable `enum` of `Error` _"things"_ to check against your Native JavaScript/Node `Errors` which often produce information that is notoriously tricky to debug without installing a slew of 3rd party tooling.

## Installation
_`yarn` is **preferred** package manager_

```bash
yarn add @theorylabs/common-errors
```

## Usage
> _Supports both `import` and `require` module usage._

```js
// Using "import" statement
import CommonErrors from '@theorylabs/common-errors'

console.log(CommonErrors)
//=> TODO
```

```js
// Using "require" statement
const CommonErrors = require('@theorylabs/common-errors')

console.log(CommonErrors)
//=> TODO
```


## License

MIT © 2021 [TheoryLabs](https://TheoryLabs.dev) | Dane@TheoryLabs.dev
