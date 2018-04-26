# Example

```shell
$ npm install sensitive-words --save
```

```javascript
const sensitive-words = require('sensitive-words').default

// ES2015 modules
import default from 'sensitive-words'

const filtered = sensitiveWords("The new apple macbook pro will have a touchbar",
		['pro', 'touchbar']
	)

console.log(filtered)
// The new apple macbook *** will have a ***
```