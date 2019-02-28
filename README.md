# profane-words

--------

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

Why: blacklisting words for whatever reason, probably. I use it for adding
`noindex` tags when serving pages that match.

License: [WTFPL](./LICENSE.md)
