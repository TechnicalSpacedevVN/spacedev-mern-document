# Kiểu dữ liệu trong TypeScript

Trong Typescript, các biến được khai báo cần chỉ định rõ kiểu dữ liệu theo cú pháp:

```typescript
let variableName: type
let variableName: type = value
const variableName: type = value
```

Trong cú pháp trên, `variableName` là tên biến và `type` là kiểu dữ liệu, ví dụ:

```typescript
let counter: number
counter = 1
counter = 'Hello' // comile error
```

Trong đoạn code trên, bạn khai báo một biến `counter` có kiểu là `number`. Khi bạn gán giá trị cho biến `counter` là `string` khác với định nghĩa ban đầu. Bạn sẽ gặp một thông báo lỗi:

```js
Type 'string' is not assignable to type 'number'
```

Điều này cảnh báo cho bạn rằng giá trị của `counter` phải là `number` như được khai báo chứ không thể là `string`