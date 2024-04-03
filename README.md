## Installation
```bash
npm install remove-duplicates-items --save-dev
```

## Import
```bash
.cjs file extension
```
```javascript
const removeDuplicates = require('remove-duplicates-items');
```
## Usage
```javascript
const removeDuplicates = require('remove-duplicates-items');

const arrayWithDuplicates = ['abc', 'bca', 'abc', 'cba'];
console.log('Array without duplicates:', removeDuplicates(arrayWithDuplicates)); // [ 'abc', 'bca', 'cba' ]
```