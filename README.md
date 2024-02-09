# TypeScript HTML Parser

<strong>HTML nodes</strong> to  <strong>Object nodes</strong>.

## Installation

```
npm i ts-html-parser -S
```

## Usage

```js
import { parse } from "romagny13-html-parser";

let html = `<!-- a comment -->
            <section>
                <h1>A title</h1>
                <p>A <strong>content</strong> with a <a href="#">Link</a></p>
            </section>
            <p>Other content</p>`;

let nodes = parse(html);
console.log(nodes);
```
