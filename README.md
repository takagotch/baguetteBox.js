### baguetteBox.js
---
https://github.com/feimosi/baguetteBox.js

```
yarn add baguettebox.js
bower install baguettebox.js --save
```

```
<a href="img/2-1.jpg"
  data-at-450="img/thumbs/2-1.jpg"
  data-at-800="img/small/2-1.jpg"
  data-at-1366="img/medium/2-1.jpg"
  data-at-1920="img/big/2-1.jpg">
    <img src="img/thumbs/2-1.jpg">
</a>

@import 'baguettebox.js/dist/baguetteBox.min.css';
```

```js
const gallery = baguetteBox.run('.gallery');
baguetteBox.show(index, gallery[0]);

baguetteBox.run('.gallery', {
});

baguetteBox.run('.gallery');

const baguetteBox = require('baguettebox.js');

import baguetteBox from 'baguettebox.js';
```

