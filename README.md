# kanaTextExtension
forked from http://mashimonator.weblike.jp/library/2012/09/javascript-3-5.html

# install
```sh
bower install kana-text-extension
```

```sh
npm install --save kana-text-extension browserify
# Use browserify. Please compiled with browserify
```

# Usage
```js
kntxtext.target = [
  ['last_name(input element name)', 'kana_last_name(input element name)', kntxtext.constant.letterType.kana, kntxtext.constant.insertType.auto],
  ['first_name', 'kana_first_name', kntxtext.constant.letterType.kana, kntxtext.constant.insertType.auto]
];
```

# Points of improvement
Input support alphabet.
