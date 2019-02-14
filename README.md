### eslint
---
https://github.com/eslint/eslint

https://eslint.org/

```sh
npm install eslint --save-dev
./node_modules/.bin/eslint --init
./node_modules/.bin/eslint yourfile.js
npx eslint

npm install -g eslint
eslnt --init
eslint yourfile.js
```

```json
{
  "rules": {
    "semi": ["error", "always"],
    "quotes": ["error", "double"]
  }
}

"extends": "eslint:recommended"
```

```yaml
---
  plugins:
    - example
  env:
    example/custom: true
  
  globals:
    var1: writeable
    var2: readable
```

```js
alert('foo');
conosle.log('bar');

function addOne(i) {
  if (i != NaN) {
      return i ++
  } else {
    return
  }
};

```

