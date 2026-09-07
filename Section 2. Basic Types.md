## TypeScript Number
总结:在这个教程中你会学到TypeScript中的数字数据类型。

所有TypeScript中的数字都是浮点数或大整数。浮点数有类型number，而大整数有类型bigint。
### The number type
这是一个浮点数变量，用于存储价格。

```typescript
let price: number = 5.15;
```
这是一个浮点数变量，用于存储价格。 
```typescript
let price: number = 5.15;
```
与 JavaScript 一样，TypeScript 支持十进制、十六进制、二进制和八进制的数字字面量：   
```typescript
// 十进制字面量
let decimal: number = 10;
// 十六进制字面量10表示16进制的10
let hex: number = 0xA;  // 值是 10
// 二进制字面量10
let binary: number = 0b1010;
// 八进制字面量12表示10
let octal: number = 0o12;
// 大整数字面量——大整数表示大于2⁵³ - 1 的整数。 
// 大整数字面量n在整数字面量末尾带有如下字符：
let big: bigint = 9007199254740991n;
```

### 概括
+ TypeScript 中的所有数字要么是浮点值（类型为数字），要么是大整数（bigint类型为大整数）。
+ 尽量少用包装对象 Number 。
<!-- 包装对象 Number 是一个类，用于创建数字对象，会导致typeof 检查返回 object 类型而不是 number 类型 -->



