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

---

```javascript {.class1 .class}
function add(x, y) {
  return x + y
}
```

---

```java {.line-numbers} 
{
int
ada
}
```

---

- [x] aaaaa
- [ ] bbbbb
- [x] ccccc
- [x] ddddd
- [x] eeeee
- [ ] fffff

---

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

表头  | 内容
---- |----
a    | b   
c    | d 

|a   |   b|
|----|----|
| c  |   d|
|^   |   e|

---

:smile:
:boy:
:girl:

---

`mark`

---


