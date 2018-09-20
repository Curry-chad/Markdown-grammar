# Markdown-grammar
 to learn to how to write markdown documents
# 1
## 2
### 3
#### 4
##### 5
###### 6
不**加粗**
*斜体*
***加粗斜体***
~~删除线~~(无效)
>这是引用的内容
>>这是引用的内容
>>>这是引用的内容<br>
分割线（>3）：
***
---
图片显示
![blockchain](C:\Users\FERSHMAN\Pictures\20170429_180849.jpg "区块链")
超链接：
[百度](http://www.baidu.com)
<br>
无序列表(无效)：
 
- 列表内容
+ 列表内容
* 列表内容

有序列表():

1. 一级列表内容   
   1. 二级有序列表
      1. 三级有序列表
2. 列表内容
3. 列表内容
<br>
表格：
姓名|年龄|性别
---|:---:|---:
chad|21|man
代码：
`System.out.println("hello java");`
多行代码:

       System.out.println("hello java");
       System.out.println("hello java");
       System.out.println("hello java");
    
#流程图
```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
