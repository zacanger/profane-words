# profane-words

--------

Aiming to be a comprehensive list of profanity in English.

For other languages, you may wish to check
[here](https://github.com/zacanger/wordlists-and-datasets/tree/master/wordlists/profanity) and
[here](https://github.com/LDNOOBW/List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words).

Installation: `npm i -S profane-words`

Usage:
```javascript
import words from 'profane-words'
const arg = process.argv[2]

if (words.includes(arg.toLowerCase())) console.warn('Watch your mouth.')
```

Why: blacklisting words for whatever reason, probably.

License: WTFPL
