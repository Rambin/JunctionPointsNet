# 使用 .NET 操作 NTFS 目录联接

[English](README.md)

## 1 原始代码来自

**[这里](https://www.codeproject.com/Articles/15633/Manipulating-NTFS-Junction-Points-in-NET)**

感谢 **jeff.brown**

## 2 修改的部分

修改了写入 **Reparse Points** 的内容，使其与 **mklink /j** 在创建指向卷GUID形式的目录（例如"\\\\?\\Volume{4bceaf62-786d-446d-a09a-8d95b9b0ff5b}"）的目录联接时的表现相同

与此同时，修改了读取目录联接目标的逻辑，使其与 **dir /a**显示的内容相同

## 3 协议

原始代码没有附带任何协议，暂且视为其进入 **公有领域**
