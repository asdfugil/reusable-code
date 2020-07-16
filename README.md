# reusable-code

reusable code

Make it so that the `reusable-code` package in https://www.youtube.com/watch?v=x03fjb2VlGY actually exists.

## Install

```bash
npm install reusable-code@latest
```
## Changelogs
Added typescript definitions
## Examples
### JavaScript
```js
const reusable = require('reusable-code')
console.log(reusable.video) //https://www.youtube.com/watch?v=x03fjb2VlGY
console.log(reusable.add2numbers(1,1)) //2
```
### Typescript
```ts
import { video,add2numbers } from 'reusable-code'
console.log(video) // https://www.youtube.com/watch?v=x03fjb2VlGY
console.log(add2numbers(4,7)) // 11
```