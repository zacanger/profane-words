# profane-words

--------

Installation: `npm i -S profane-words`

Usage:
```javascript
import { de, en, es, fr, it, nl, pt, ru } from 'profane-words'
const arg = process.argv[2]

if (en.includes(arg)) console.warn('Watch your mouth.')
```

Why: blacklisting words for whatever reason, probably.

License: WTFPL
