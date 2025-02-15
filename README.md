## drag-easy-components

A lightweight JavaScript library for creating draggable web components written in TypeScript (Rollup.js bundler)

## Installation

Using NPM:

```bash
npm install drag-easy-components
```

Using a `<script>` tag (UMD version):

```JavaScript
<script src="node_modules/drag-easy/dist/drag-easy.umd.js"></script>
```

Basic Usage

```JavaScript
import { makeDraggable } from "drag-easy-components";
const box = document.getElementById("box");
makeDraggable(box);
```

HTML (Without a Bundler)

```HTML
<script src="node_modules/drag-easy/dist/drag-easy.umd.js"></script>
<script>
    const box = document.getElementById("box");
    DragEasy.makeDraggable(box);
</script>
```

## Documentation

For more details, visit the official [documentation](https://drageasycomponents.com)
