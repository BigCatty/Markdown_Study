## 1. 标题
```html
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
## 2. 段落格式
### 2.1 换行
this is a text. `1. 末尾附加两个或两个以上空格实现换行`
`2. 或者直接添加一个空行`
this is a text.
### 2.2 字体
```html
*斜体文本*

**粗体文本**

***粗斜体文本***
```
*斜体文本*

**粗体文本**

***粗斜体文本***
### 2.3 分隔线
```html
this is a text.
***
this is a text.
```
this is a text.
***
this is a text.
### 2.4 删除线
```html
~~被删除的文本~~
```
~~被删除的文本~~
### 2.5 下划线
```html
<u>带下划线的文本</u>
```
<u>带下划线的文本</u>
### 2.6 脚注
```html
带脚注的文本[^FOOTER]

[^FOOTER]: this is the footer.
```
带脚注的文本[^FOOTER]

[^FOOTER]: this is the footer.
## 3. 列表
### 3.1 无序列表
```html
* 第1项
* 第2项
* 第3项
```
* 第1项
* 第2项
* 第3项
### 3.2 有序列表
```html
1. 第1项
2. 第2项
3. 第3项
```
1. 第1项
2. 第2项
3. 第3项
### 3.3 列表嵌套
```html
1. 第一项
    * 第1.1项
    * 第1.2项
    * 第1.3项
2. 第二项
    * 第2.1项
    * 第2.2项
    * 第2.3项
```
1. 第一项
    * 第1.1项
    * 第1.2项
    * 第1.3项
2. 第二项
    * 第2.1项
    * 第2.2项
    * 第2.3项
## 4. 区块
### 4.1 区块
```html
> 区块 
> this is a text.this is a text.this is a text.this is a text.this is a text.this is a text.this is a text.this is a text.this is a text.this is a text.this is a text.this is a text.this is a text.this is a text.
```
> 区块 
> this is a text.this is a text.this is a text.this is a text.this is a text.this is a text.this is a text.this is a text.this is a text.this is a text.this is a text.this is a text.this is a text.this is a text.
### 4.2 区块嵌套
```html
> 最外层
>> 第一层
>>> 第二层
>>>> 第三层
```
> 最外层
>> 第一层
>>> 第二层
>>>> 第三层
### 4.3 区块中使用列表
```html
> 区块中的列表
> 1. 第一项
>     * 第1.1项
>     * 第1.2项
>     * 第1.3项
> 2. 第二项 
>     * 第2.1项
>     * 第2.2项
>     * 第2.3项
```
> 区块中的列表
> 1. 第一项
>     * 第1.1项
>     * 第1.2项
>     * 第1.3项
> 2. 第二项 
>     * 第2.1项
>     * 第2.2项
>     * 第2.3项
### 4.4 列表中使用区块
```html
* 第一项
    > 区块1.1
    
    > 区块1.2
* 第二项
    > 区块2.1
    
    > 区块2.2
```
* 第一项
    > 区块1.1

    > 区块1.2
* 第二项
    > 区块2.1
    
    > 区块2.2
## 5. 代码
### 5.1 代码片段
> 使用``来包围print()

`print()` 函数
### 5.2 代码区块
> 使用``````来包围区块，可以指定语言类型
```javascript
$(document).ready(function () {
    alert('RUNOOB');
});
```
```python
for item in items:
    print(item)
```
## 6. 链接
```html
[百度](https://www.baidu.com)

<https://www.baidu.com>
```
[百度](https://www.baidu.com)

<https://www.baidu.com>
## 7. 图片
```html
![图片](./123.png)
<img src="./123.png" width="100px">
```
![图片](./123.png)
<img src="./123.png" width="100px">
## 8. 表格
### 8.1 一般格式
```js
|表头|表头|
|---|---|
|单元格|单元格|
|单元格|单元格|
|单元格|单元格|
```
|表头|表头|
|---|---|
|单元格|单元格|
|单元格|单元格|
|单元格|单元格|
### 8.2 对齐方式
```js
|<---向左对齐|<-居中对齐->|向右对齐--->|
|:---|:---:|---:|
|单元格|单元格|单元格|
|单元格|单元格|单元格|
|单元格|单元格|单元格|
```
|<---向左对齐|<-居中对齐->|向右对齐--->|
|:---|:---:|---:|
|单元格|单元格|单元格|
|单元格|单元格|单元格|
|单元格|单元格|单元格|
