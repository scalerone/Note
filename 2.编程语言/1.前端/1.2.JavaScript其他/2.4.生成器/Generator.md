# Generator

## 什么是生成器

+ 生成器是一个通过构造函数 Generator 创建的对象

+ 生成器既是一个迭代器，同时又是一个可迭代对象

## 创建生成器

+ 生成器的创建必须使用生成器函数（Generator Function）

+ 创建方式1

  ```js
  // 这是一个生成器函数，该函数一定返回生成器
  function* method() {

  }
  ```

+ 创建方式2

  ```js
  // 这是一个生成器函数，该函数一定返回生成器
  function *method() {

  }
  ```

## 生成器内部如何执行

+ 生成器内部为了给生成器的每次迭代提供数据

+ 每次调用生成器的 `next` 方法，将导致生成器函数运行到下一个 yield 关键字位置

## yield

+ 是一个关键字

+ 该关键字智能在生成器函数内部使用

+ 表达“生成”一个迭代数据
