变量和函数都具有作用域。作用域就是变量和函数的可被访问的范围，控制着变量和函数的可见性和生命周期。




## 变量的作用域
var msg = "this is message";// 定义全局变量 msg
```

除了上述定义全局变量外，还有一种比较特殊的方式定义全局变量（具体用法如下述代码）。但这种特殊用法并不推荐！
function fun(){
```

### 局部变量

```javascript
function fun(){
```

### 声明提前


#### 全局变量声明提前
console.log( msg );// 不会报错，输出 undefined
```

上述代码中的第一行输出不会报错，而是输出 undefined值。效果等同于如下述代码:

```javascript
var msg;// 定义全局变量 msg，但未初始化
```

#### 局部变量声明提前
function fn(){
```

效果等同于如下述代码:

```javascript
function fn(){
```

### 按值传递

var n = 100;// 全局变量n
```

## 函数的作用域
function fn( num1, num2){
```

### 内部函数
function outer(){// 全局函数
```