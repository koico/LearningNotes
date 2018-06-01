一些MarkDown使用习惯
---
>引用
---
- 1
- 2
- 3
---
* 1
* 2
* 3
---
+ 1
+ 2
+ 3
---
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
```javascript {.class1 .class}
function add(x, y) {
  return x + y
}
```

```java {.line-numbers} 
{
int
ada
}
```

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

- [x] aaaaa
- [ ] bbbb

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

表头  | 内容
---- |----
你好|哈哈
ahhaha |hahaha 


|a   |  b|
|----|----|
|   |d|
|^  |e|


:smile:
:fa-car:
:boy:
:girl:


[^1]: Hi! This is a footnote
[^2]:haha! This

==mark==
`mark`



