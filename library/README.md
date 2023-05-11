<h1 align="center"><code>nopopup.js</code></h1>

<p align="center">Prevent popup boxes in JavaScript</p>

## ⚙️ Installation

```terminal
npm i nopopup
```

**CDN Links:**
- https://cdn.jsdelivr.net/npm/nopopup
- https://www.unpkg.com/nopopup

## 📖 Usage

#### ◉ Import

```js
// ES6
import nopopup from "nopopup";

// commonjs
const nopopup = require("nopopup");
```

#### ◉ Disable all popup boxes

```js
import nopopup from "nopopup";

nopopup();

// Test it!
alert('hello');
confirm('world');
```

#### ◉ Disable specific popup boxes

```js
import nopopup from "nopopup";

nopopup(["alert"]);

// Test it!
alert('hello');
confirm('world');
```

---

[Support me on Patreon](https://www.patreon.com/axorax) — 
[Check out my socials](https://github.com/axorax/socials)