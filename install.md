# 安装TypeScript
## 安装命令
```bash
npm install -g typescript
```
验证是否安装成功
```bash
tsc -v
```
## 第一个脚本
创建一个文件，`hello.ts`。
```bash
vim hello.ts
```
输入如下脚本
```typescript
var message:string = "Hello World" 
console.log(message)
```
### 编译
```bash
tsc hello.ts
```
执行后会生成一个`hello.js`
### 执行
运行如下脚本
```bash
node hello.js
```
可以看到命令行输出了`Hello World`。
