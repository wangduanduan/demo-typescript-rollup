# demo-typescript-rollup
Project which demonstrates Rollup bundling of TypeScript modules.

Rollup plugin used:
https://www.npmjs.com/package/rollup-plugin-typescript

To perform Rollup bundling execute:
```
npm run bundle
```
...or execute Rollup manually:
```
rollup -c
```

To run the output bundle (Node.js required):
```
npm run start
```
or run Node manually:
```
node dist\bundle.js
```

Examples:
```
>npm run bundle
> demo-typescript-rollup@1.0.0 bundle C:\dev\github\demo-typescript-rollup
> rollup -c
```
```
src/index.ts → dist/bundle.js...
created dist/bundle.js in 78ms
```
```
>npx rollup -c
src/index.ts → dist/bundle.js...
created dist/bundle.js in 71ms
```
```
>npm run start
> demo-typescript-rollup@1.0.0 start C:\dev\github\demo-typescript-rollup
> node dist/bundle.js

Hello, world!
```
```
>node dist\bundle.js
Hello, world!
```

Terminal commands used in creation of this project:
```
npm init -y
npm install --save-dev typescript rollup rollup-plugin-typescript tslib
```

