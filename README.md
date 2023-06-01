# svelte-v4-custom-element-slots

Demos an issue using slots with custom elements in Svelte 4 (pre-release) when **no** shadow root is in use.


## Get started

```bash
git clone https://github.com/patricknelson/svelte-v4-custom-element-slots.git
cd svelte-v4-custom-element-slots
npm i
npm run dev
```


## From scratch

Init base files

```bash
# select Svelte + JavaScript
npm init vite

# Install but overwrite with Svelte v4
npm i -D svelte@4.0.0-next.0
```

Update Svelte compiler options in `vite.config.js` to enable custom elements, i.e. `customElement: true`.
