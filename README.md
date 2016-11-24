# profane-words

--------

Aiming to be a comprehensive list of profanity in English.

Installation: `npm i -S profane-words`

Usage:
```javascript
import words from 'profane-words'
const arg = process.argv[2]

if (words.includes(arg.toLowerCase())) console.warn('Watch your mouth.')
```

Why: blacklisting words for whatever reason, probably.

License: WTFPL
