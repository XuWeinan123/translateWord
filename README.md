# 如何使用这个插件
> 这个插件的作用是通过一个 Json 文件对设计文档中的一些词条进行替换。适用于设计稿快速准确的转为不同语言的版本

## 使用教程
1. 首先你需要有一个 Json 文件来保存需要翻译的词条。它满足以下的格式：

```
{
    "items": [
        {
            "zh": "中文",
            "en": "English"
        }
    ]
}
```
items 属性：所有的词条
zh 属性：词条对应的中文
en 属性：词条对应的英文

2. Json 文件需要可以使用一个网址获取，比如
[](https://raw.githubusercontent.com/XuWeinan123/translateWord/master/example.json)
打开这个网址之后看到的效果应该是这样的：
![](https://tva1.sinaimg.cn/large/007S8ZIlgy1ghlhs873yxj31b30c20u0.jpg)

3. 打开插件，输入刚才的网址。
4. 选中之后点击对应的翻译即可！