# HOMEWORK REQUIREMENT
![MOCKUP](mockups/mockup.png)

1. 小步提交，至少3个提交
2. 按照效果图完成作业
3. 样式参数定义可依据src/style/_variables.scss
4. (**扩展**)若无后端，可以选择使用Json Server返回模拟数据
    
    - 启动Json Server（参加Setup 3）
    - `http://localhost:3000/users/1`获取user基本信息
    - `http://localhost:3000/users/1/educations`获取user教育信息
5. (**扩展**)操作DOM可使用jQuery
**设置元素的内容**

    ```javascript
    $('#id').html("value");
    ```
    
    **在元素结尾插入内容**
    
    ```javascript
    const item = 'Item 1';
    $('ul').append(`<li>${item}</li>`)
    ```
6. (**扩展要求！**)通过eslint测试（命令参加Setup 4）

# Setup

1.安装包依赖

```
npm install
```

2.启动服务 localhost:1234，更新文件会实时加载

```
npm start
```

3.启动Json Server http://localhost:3000
```
npm run server
```

4.代码风格检测：

```
npm run lint
```
