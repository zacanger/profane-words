# profane-words

[![Support with PayPal](https://img.shields.io/badge/paypal-donate-yellow.png)](https://paypal.me/zacanger) [![Patreon](https://img.shields.io/badge/patreon-donate-yellow.svg)](https://www.patreon.com/zacanger) [![ko-fi](https://img.shields.io/badge/donate-KoFi-yellow.svg)](https://ko-fi.com/U7U2110VB)

A semi-comprehensive list of profanity in English.

*Warning* don't read the list if you're easily offended. I don't even know
what at least half of these words mean.

This includes words from several other lists, with some 'ok words' filtered out.

For other languages, you may wish to check
[here](https://github.com/LDNOOBW/List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words).

Installation: `npm i -S profane-words`

Usage:

```javascript
import words from 'profane-words'
const arg = process.argv[2]

if (words.includes(arg.toLowerCase())) {
  console.warn('Watch your mouth.')
}
```

All words are lowercased.

Why: disallowing words for whatever reason, probably.

License: [WTFPL](./LICENSE.md)
