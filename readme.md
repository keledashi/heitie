> 访问:  
> https://keledashi.github.io/heitie/  
# ■ vue基础
## 1.vue实例与模板语法
- 创建实例 
- 插值
  - 双大括号`{{ }}`
- 指令
  - 以`v-`开头
  - 自定义指令
- 方法methods

## 2.数据绑定
- 单向绑定
- 双向绑定
- 表单收集
  - 普通文本
  - 单选框
  - 复选框
  - 文本域
  - 下拉框
  - `v-model`修饰符:`number`,`lazy`,`trim`
## 3.事件处理
- 基本使用
  - 不传参
  - 传参 `$event`
- 事件修饰符
  - `prevent` 阻止默认事件
  - `stop` 阻止事件冒泡
  - `once` 事件只触发一次
  - `capture` 使用事件的捕获模式
  - `self` 只有event.target是当前操作的元素时才出发事件
  - `passive` 事件的默认行为立即执行，无需等待事件回调
- 常用按键事件别名
  - `enter` 回车
  - `delete` 删除和退格
  - `esc` 退出
  - `space` 空格
  - `tab` 切换
  - `up` `down` `left` `right` 上下左右

## 4.计算属性与侦听器
- 计算属性与其他对比(案例名字拼接)
  - 插值法
    - 使用v-model，但是复杂处理比较麻烦
  - methods法
    - 优化插值时复杂的处理，但是效率低，因为每次更新都会调用执行
  - 计算属性法
    - computed 初始化执行和变化时执行
    - 只是获取，可以用简写方式
    - 如果既要获取也要修改，要完整写get和set

- 侦听器(监视属性)
  - 作用：当监视的属性改变时，可以获取新值和旧值
  - 目标：可以监视data属性，也可以监视计算属性
  - `immediate:true` 一开始就监视
  - `deep:true` 对象深度监视
  - `handler()` 进行监视处理的函数
  - 深度监视
  - 可以简写，前提是只要handler

- 过滤器(不常用)

## 5.class与style绑定
- class绑定(常见)
  - 字符串写法
    - 场景：单个class名不确定
  - 数组写法
    - 场景：class名个数不确定，名字不确定
  - 对象写法
    - 场景：class名个数确定，名字确定，只是动态决定用不用
- style绑定(少见)
  - 对象写法
  - 对象放数组后写法

# ■ vue组件化
## 非单文件组件
- 局部注册
- 全局注册
## 单文件组件
- template
- script
- style
# ■ vue-cli
- 安装
  ```
  npm install -g @vue/cli
  ```
- 查看版本
  ```
  vue --version
  ```
- 创建工程
  ```
  vue create xxx
  ```
- 启动项目
  ```
  npm run serve
  ```
# ■ vue-router

# ■ vuex

# ■ element-ui

# ■ vue3