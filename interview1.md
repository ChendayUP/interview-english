# Front-End-Tech-Interview
收集常用前端术语的中英翻译和技术英语常用表达

# 📇常用标点符号和运算符

| Term                                  | Translation        | Phonetics       |
| ------------------------------------- | ------------------ | --------------- |
| double quotes                         | 双引号             | [ˈdʌbəl kwəʊts]   |
| single quotes                         | 单引号             | [ˈsɪŋɡəl kwəʊts] |
| decimal                               | 小数点             | [ˈdɛsɪməl]       |
| operator                              | 运算符             | [ˈɒpəreɪtər]      |
| operand                               | 操作数             | [ˈɒpərænd]       |
| lowercase letters                     | 小写字母           | [ˈloʊərˌkeɪs ˈlɛtərz] |
| uppercase letters                     | 大写字母           | [ˈʌpərˌkeɪs ˈlɛtərz] |
| an underscore                         | 下划线             | [ən ˈʌndərˌskɔr] |
| Hyphens                               | 连字符             | [ˈhaɪfənz]       |
| Curly braces                           | 花括号 {}         | [ˈkɜrli breɪsɪz] |
| Curly brackets                         | 花括号 {}         | [ˈkɜrli ˈbrækɪts]|
| double equal signs                     | 双等号             | [ˈdʌbl ˈiːkwəl saɪnz] |
| triple equal signs                     | 三等号             | [ˈtrɪpl ˈiːkwəl saɪnz] |
| parentheses / round brackets          | 小括号（）         | [pəˈrɛnθəsiz]    |
| square brackets                        | 方括号[]           | [skwɛr ˈbrækɪts]  |
| question mark                          | 问号?              | [ˈkwɛsʧən mɑrk]  |
| exclamation mark                       | 感叹号！           | [ˌɛkskləˈmeɪʃən mɑrk] |
| star sign / asterisk                   | 星号 *            | [stɑr saɪn / ˈæstərɪsk] |
| ampersand                              | &                 | [ˈæmpərsænd]     |
| percent sign                           | 百分号 %          | [pərˈsɛnt saɪn] |
| less than sign                          | 小于号 <          | [lɛs θæn saɪn]  |
| greater than sign                      | 大于号 >          | [ˈɡreɪtər θæn saɪn] |
| the forward slash                      | 前斜杠 /          | [ðə ˈfɔrwərd slæʃ] |
| backslash                              | 后斜杠 \          | [ˈbækslæʃ]       |
| checkmark                              | 勾号 √            | [ˈʧɛkmɑrk]       |
| semicolon                              | 分号 ;            | [ˈsɛmɪˌkoʊlən]   |
| colon                                  | 冒号 :            | [ˈkoʊlən]        |
| ellipses                               | 省略号 ...         | [ɪˈlɪpsiz]        |
| comma                                  | 逗号 ,            | [ˈkɒmə]           |
| period / full stop                     | 点 .              | [ˈpɪriəd / fʊl stɑp] |
| Upper Camel Case （也叫 Pascal Case）   | 驼峰命名法（大写） | [ˈʌpər ˈkæməl keɪs] |
| Lower Camel Case                       | 驼峰命名法（小写） | [ˈloʊər ˈkæməl keɪs] |
| The addition operator                  | + 加号             | [ðə əˈdɪʃən ˈɒpəreɪtər] |
| The multiplication operator            | * 乘号             | [ðə ˌmʌltɪplɪˈkeɪʃən ˈɒpəreɪtər] |
| Subtraction                            | 减法               | [səbˈtrækʃən]    |
| Division                               | 除法               | [dɪˈvɪʒən]        |
| Exponentiation                         | 乘方               | [ɪkˌspoʊnənʃiˈeɪʃən] |
| Modulus                                | 模量               | [ˈmɒdʒʊləs]       |
| capital letter                         | 大写字母           | [ˈkæpɪtl ˈlɛtər]  |



## 🎈CSS

| Term                       | Translation    |
| -------------------------- | -------------- |
| attribute                  | 属性           |
| property                   | 属性           |
| Shorthand property         | 简写属性       |
| The box model              | 盒模型         |
| a block level element      | 块级元素       |
| an inline element          | 内联元素       |
| a pseudo class             | 伪类           |
| ID Selector                | id 选择器      |
| class selector             | 类选择器       |
| Attribute selectors        | 属性选择器     |
| Universal Selector         | 通配选择器     |
| Type selectors             | 元素选择器     |
| Grouping Selector          | 标签选择器     |
| Descendant Selector        | 后代选择器     |
| Child Selector             | 直接子代选择器 |
| Adjacent Sibling Selector  | 相邻兄弟选择器 |
| General sibling combinator | 一般兄弟选择器 |
| External CSS               | 外部 CSS       |
| Internal CSS               | 内部 CSS       |
| absolute positioning       | 绝对定位       |
| Responsive Design          | 响应式设计     |
| Adaptive Design            | 自适应设计     |
| CSS preprocessors          | CSS 预处理器   |
| Cascading Order            | 级联顺序       |
| an inline style            | 内联样式       |
| Opacity                    | 不透明度       |
| Transparency               | 透明度         |
| Progressive enhancement    | 渐进增强       |
| Graceful degradation       | 优雅降级       |
| dotted line                | 点虚线         |
| solid line                 | 实线           |
| rounded corner             | 圆角           |
| the parent element         | 父元素         |
| be inherited from          | 继承自         |

## 🌴attribute 和 property 的区别

以下是 ChatGPT 的解释：

在前端领域中，attribute 和 property 都指的是 HTML 元素的特性。

Attribute 是 HTML 元素在 HTML 文件中定义的特性，用于在 HTML 文件中初始化元素的值。例如：

```
<input type="text" value="hello" id="myInput">
```

在这个例子中，`type`、`value` 和 `id` 都是 attribute。

Property 是 JavaScript 中的对象属性，用于在 JavaScript 代码中对元素进行操作。例如：

```
const input = document.getElementById('myInput');
input.value = 'hello';
```

在这个例子中，`value` 是 property。

注意，在 JavaScript 中，HTML 元素会被表示为对象，每个 attribute 对应一个 property。例如，上面的 HTML 中的 `value` attribute 对应了 JavaScript 中的 `input.value` property。但是，这两者并不完全相同，property 的值可以在 JavaScript 代码中改变，而 attribute 的值只能在 HTML 中指定。

# 🔖JS

| 术语                                    | 中文翻译                 | 例句               |
| --------------------------------------- | ------------------------ | ------------------------ |
| Primitive types                         | 原始数据类型             |              |
| Non-primitive types                     | 引用数据类型             |              |
| literal                                 | 字面量                   |                    |
| Hoisting                                | 变量提升                 | the local variable “x” is hoisted inside the local scope |
| Global Scope                            | 全局作用域               |                |
| Function scope                          | 函数作用域               |                |
| Block Scope                             | 块级作用域               |                |
| Implicit Type Coercion                  | 隐式类型转换             |              |
| Type coercion                           | 强制类型转换             |              |
| a dynamically typed language            | 动态类型语言             |              |
| a statically typed language             | 静态类型语言             |              |
| call a function                         | 调用一个函数             |              |
| invoke                                  | 调用                     | The function is invoked when a button is clicked |
| be executed                             | 被执行                   |                    |
| override                                | 覆盖                     | It *will override external and internal styles and browser defaults.* |
| global scope object                     | 全局作用域对象           |            |
| instructions                            | 指令                     |                      |
| Directive                               | 指令                     |                      |
| JavaScript Statements                   | JavaScript 语句          |           |
| a block variable                        | 块级变量                 |                  |
| a block constant                        | 块常量                   |                    |
| Case Sensitive                          | 大小写敏感的             | JavaScript is Case Sensitive |
| case-insensitive                        | 大小写不敏感的           |            |
| ternary operator (Conditional operator) | 三元运算符               |                |
| Arrow function                          | 箭头函数                 |                  |
| Destructuring assignment                | 解构赋值                 |                  |
| Rest parameters                         | 剩余参数                 |                  |
| Deep copy                               | 深拷贝                   |                    |
| Shallow copy                            | 浅拷贝                   |                    |
| the prototype chain                     | 原型链                   |                    |
| throw an exception (throw an error)     | 报错                     |                      |
| Higher-order function                   | 高阶函数                 |                  |
| Closure                                 | 闭包                     |                      |
| Execution Contexts                      | 执行上下文               |                |
| Spread Operator                         | 拓展运算符               |                |
| Self-Invoking Functions                 | 立即执行函数、自执行函数 |  |
| immediately invoked function            | 立即调用函数             |              |
| Asynchronous functions                  | 异步函数                 |                  |
| Synchronous functions                   | 同步函数                 |                  |
| single-threaded                         | 单线程的                 |                  |
| Multi-threaded                          | 多线程的                 |                  |
| Event Loop                              | 事件循环                 |                  |
| microtasks                              | 微任务                   |                    |
| macrotasks                              | 宏任务                   |                    |
| spread syntax          | 拓展语法       |        |
| rest syntax            | 剩余语法       |        |
| a curry function       | 一个柯里化函数 |  |
| currying               | 柯里化         |          |
| static class members   | 静态类成员     |      |
| task queue             | 任务队列       |        |
| immutability           | 不可变性       |        |
| the same-origin policy | 同源策略       |        |
| event delegation       | 事件委托       |        |
| event capturing        | 事件捕获       |        |
| Event Bubbling         | 事件冒泡       |        |
| Event propagation      | 事件传播       |        |

# 💥React

| 术语                    | 中文翻译       |
| ----------------------- | -------------- |
| two-way data binding | 双向数据绑定 |
| Single-page Application | 单页应用       |
| Controlled Components   | 受控组件       |
| Uncontrolled Components | 非受控组件     |
| stateless components    | 无状态组件     |
| stateful components     | 有状态组件     |
| lifecycle methods       | 生命周期方法   |
| reconciliation          | 协调           |
| decorators              | 装饰器         |
| Server-Side Rendering   | 服务器端渲染   |
| a switching component   | 切换组件       |
| pass params to          | 传递参数       |
| the parent element | 父元素|
|  a shared parent | 共享父类 |
| reusable, nestable components | 可重复使用、可嵌套的组件 |

# 🍁技术英语表达

| 术语                    | 中文翻译       | 例句 |
| ----------------------- | -------------- |-----------------|
| Under the hood          | 这个比较难直译，大意是内部机制或细节 | Under the hood, it uses Babel and webpack, but you don’t need to know anything about them.( from react doc) |
| wrap XXX in (into) XXX | 把什么包裹在什么里面 |Therefore, to pass a JS object in JSX, you must wrap the object in another pair of curly braces |
| deploy to production | 部署到生产 | When you’re ready to deploy to production, running npm run build will create an optimized build of your app in the build folder. |
| First Contentful Paint |  “首次内容可见时间”。它是指在浏览器中加载网页时，首次可以显示出页面内容的时间（不包括图片）||
| Largest Contentful Paint |  “最大内容可见时间”。它是指页面中最大的内容元素（例如图像、视频或文本）出现在浏览器中可见的时间。||
| Don’t Repeat Yourself （DRY） | 不重复造轮子。（也叫 DRY 法则） |The most important principle for structuring state is to keep it DRY (Don’t Repeat Yourself). |
| Built-in                | 内置的         | |
| Expressions             | 表达式         | |
| Comment                 | 注释          | |
| interactivity           | 交互性         | |
| specified               | 指定的         | |
| Fixed values                          | 固定值             | |
| pipeline | 在技术领域，pipeline 指的是一系列有先后顺序的相关的任务或开发流程。 | it just creates a frontend build pipeline |
| toolchains | 工具链 | |
| Breakpoint |断点 | set breakpoint 设置断点 |
| Fields | 字段 （表单中的） | |
| Search Engine Optimization | 搜索引擎优化 SEO ||
| Semantic HTML |语义化的HTML ||
|  What You See is What You Get | 所见即所得 一般可以缩写为 WYSIWYG | |
| a tic-tac-toe game | 井字游戏| |
| minify | 简化 | I used a program to minify my code.|
| inspect | 检查 | |
| nesting components | 嵌套组件 | |
| on-demand | 按需 | Figure out the absolute minimal representation of the state your application needs and compute everything else on-demand |
| inverse data flow | 逆向数据流 | |
| Spot the mistake  | 发现错误 | |
| landing screen | 登陆界面 | |
| Adjacent | 相邻的 | Adjacent JSX elements must be wrapped in an enclosing tag |
| legible | 可读的 | |
