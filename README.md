# vite-ts
Demo project from Vite `vanilla-ts` template. Please run the following script after checkout.

```
npm install
```

## For development mode

Vite dev server/esbuild doesn't respect ES target in `tsconfig.json` file because it still generate private method without polyfill.

```
npm run dev
```
![image](https://user-images.githubusercontent.com/442046/232254016-b90649a7-4682-47ca-af3c-0d72231c8c61.png)

## For production mode
It seems to work as expected.

```
npm run build
npm run preview
```
![image](https://user-images.githubusercontent.com/442046/232254113-3aa8ea62-5e44-47c9-b258-0ba65834f07a.png)
