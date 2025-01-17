# DOMiNATIVE-Vue

### **Quirks and hacks for Vue 3 to work with [DOMiNATIVE](https://github.com/SudoMaker/DOMiNATIVE) on [NativeScript](https://nativescript.org/)**

[Playground](https://stackblitz.com/edit/nativescript-dominative-vue-3?file=app/App.vue)

---

## Installation

Via npm:

```shell
npm install @dominative/vue @nativescript/core dominative undom-ng vue
```

**Note:** `@nativescript/core`, `dominative`, `undom-ng`, `vue` are peer dependencies, you have to install them manually.

---

## Usage

```js
import { Application } from '@nativescript/core'
import { createApp } from '@dominative/vue'
import App from 'App.vue'

const app = createApp(App)

// Start the app
app.$run()

```

---

## License

MIT
