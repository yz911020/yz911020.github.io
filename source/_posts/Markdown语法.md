---
title: Markdown
date: 2024-10-28T15:01:00
tag:
---

# 一、标题

```
# 一级标题
## 二级标题
######最多支持6级
```
# 二、引用
Markdown中的引用和 email 中用「>」的引用类似，只需在段落的第一行最前面加上「>」，引用可嵌套，只要加上不同数量的「>」就行，如下所示效果: 
>这是引用内容
>> 引用内容
>回到一级引用
# 三、列表
**有序列表**：使用数字接着一个英文句点
1. red
2. blue
**无序列表**: 使用加号，减号
- red
- blue
**代办列表**：-[] 前后都要有空格
```
-  [ ] 代办事项
-  [x] 代办事项
```
-  [ ] 代办事项
-  [x] 代办事项
# 四、代码
代码块在`之间，指定一个语言标识符，就可以启用语法高亮。 例子，一段PHP代码：
```PHP
//评论等级和博主认证

function get_author_class($comment_author_email,$user_id){

    global $wpdb;
    
    $author_count = count($wpdb->get_results(
    
    "SELECT comment_ID as author_count FROM $wpdb->comments WHERE 
    
    comment_author_email = '$comment_author_email' "));
    
}
```
# 五、强调
使用 * 和 _ ， 一个表示斜体，二个表示加粗
~~~
*斜体* 
_斜体_
**加粗** 
__加粗__
~~~
*斜体* _斜体_
**加粗** __加粗__
# 六、链接
~~~
[百度](https://www.baidu.com)
~~~
[百度](https://www.baidu.com)
# 七、表格

| 手机  | 显示器 | 电脑  |
| :-: | :-: | :-: |
| 苹果  | 三星  | 微软  |
```

水果 | 粗粮 | 饮料
:---: | :---: | :---:
苹果 | 大米 | 可乐
```

| 水果  | 粗粮  | 饮料  |
| :-: | :-: | :-: |
| 苹果  | 大米  | 可乐  |
# 八、分割线
```
分隔线以上
---
分隔线以下
```
分隔线上

---
分隔线下

# 九、图片
```
![灭霸宝石大全](https://avatars.githubusercontent.com/u/32013931?v=4)
```
![图片](https://avatars.githubusercontent.com/u/32013931?v=4)




