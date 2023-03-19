# profane-words

A semi-comprehensive list of profanity in English.

*Warning* don't read the list if you're easily offended. I don't even know
what at least half of these words mean.

This includes words from several other lists, with some 'ok words' filtered out.
*Note* because this project started out as a compilation of other lists, there
may still be false positives that I missed here! If you come across something
that doesn't make sense, please open an issue or a PR!

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
