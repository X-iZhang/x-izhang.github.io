---
# To publish author profile pages, remove all the `_build` and `cascade` settings below.
# _build:
#   render: never
# cascade:
#   _build:
#     render: never
#     list: always
---




这部分代码的意思是它阻止了作者简介页面的渲染。如果你想发布作者简介页面，你需要移除或注释掉 `_build` 和 `cascade` 设置。

例如：

```yaml
# _build:
#   render: never
# cascade:
#   _build:
#     render: never
#     list: always
```