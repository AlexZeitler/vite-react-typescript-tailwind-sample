# vite-react-typescript-tailwind-sample

## About

Minimal [Vite](https://vitejs.dev) + [React](https://reactjs.org/) sample based on `yarn create @vitejs/app vite-react-typescript-tailwind-sample --template react-ts` including [tailwindcss](https://tailwindcss.com/).

![Screenshot](assets/screenshot.png)

## Usage

```bash
yarn
yarn dev
```

## Explanation

After running `yarn create @vitejs/app <MyApp> --template react-ts`, just run `yarn add --dev tailwindcss@latest postcss@latest autoprefixer@latest` and add these files:

* [postcss.config.js](https://github.com/AlexZeitler/vite-react-typescript-tailwind-sample/commit/cbf46b58e2185987280184c7865d6033e5176cce#diff-05ed1c7f99e45b485708115502a1e0f28c8547e9a9a29c1b8664f79103cf7873)

* [src/App.css](https://github.com/AlexZeitler/vite-react-typescript-tailwind-sample/commit/cbf46b58e2185987280184c7865d6033e5176cce#diff-60f5dcfc15327d5dd812d9df394c217efbedb4aa33dca782ed69d39dce811972)

* [tailwind.config.js](https://github.com/AlexZeitler/vite-react-typescript-tailwind-sample/commit/cbf46b58e2185987280184c7865d6033e5176cce#diff-ddc1067f080930bc48865f4660316a14b21bbc9f9ba85975ce8479342b983d2e)

* `import './App.css'` in `src/main.tsx` [Details](https://github.com/AlexZeitler/vite-react-typescript-tailwind-sample/commit/cbf46b58e2185987280184c7865d6033e5176cce#diff-1cd8b18798a1a103bfe13bef54354c1f3a3bea29a31c8eea1a0c67a3a839b811R3)

## LICENSE

MIT License

Copyright (c) 2021 Alexander Zeitler

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
