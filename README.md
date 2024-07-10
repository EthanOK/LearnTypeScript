doc:
https://www.runoob.com/typescript/ts-tutorial.html

https://www.typescriptlang.org/docs/

安装 typescript：

```
npm install -g typescript
npm install -g ts-node
```

安装完成后我们可以使用 tsc 命令来执行 TypeScript 的相关代码:
`tsc -v`

# ts 编译 js

hello.ts

```ts
const str: string = "helle ts";
console.log(str);
```

`tsc hello.ts`

hello.js

```js
var str = "helle ts";
console.log(str);
```

`node hello.js`

# 直接运行 ts
`ts-node hello.ts`
