# DROP USER

移除一个数据库角色。

## 概要

```
DROP USER [IF EXISTS] name [, ...]
```
## 描述

DROP USER 是一个被弃用的命令，不过为了向后兼容仍然可以使用。组（用户）已经被更加通用的概念角色替代。 更多详细信息见 [DROP ROLE](./drop-role.md) 。

## 参数

IF EXISTS

如果该角色不存在则不要抛出一个错误，而是发出一个提示。

name

一个存在的角色的名称。

## 兼容性

在 SQL 标准中没有 DROP USER 命令。 SQL 标准把用户的定义留给具体实现自行解释。

## 另见

[DROP ROLE](./drop-role.md)

**上级主题：** [SQL命令参考](./README.md)
