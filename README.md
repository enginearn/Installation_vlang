# The V Programming Language

This directory contains projects written in V.

## Installation

To install V, follow the instructions in the [V README](https://github.com/vlang/v#installing-v-from-source).

And also execute the following command to recgognize the V language commands:

[Getting Started With V](https://blog.vlang.io/getting-started-with-v/)

``` PowerShell
> .\v symlink
```

After that, you can run the following command to check if V is installed correctly:

``` PowerShell
> v version
V 0.3.3 9794a23
```

## Projects

<details>
<summary>v new PROJECT</summary>

``` PowerShell
> v new hello_vlang
Input your project description: Input your project version: (0.0.0)
Input your project license: (MIT)
Initialising ...
Complete!
```

``` PowerShell
> cd hello_vlang
> ls

    Directory: C:\Users\path\to\Development\vlang\v_projects\hello_vlang

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d----          2023/02/07    22:30                src
-a---          2023/02/07    22:30            139 .editorconfig
-a---          2023/02/07    22:30            148 .gitattributes
-a---          2023/02/07    22:30            246 .gitignore
-a---          2023/02/07    22:30            106 v.mod
```

</details>

<details>
<summary>v run</summary>

``` PowerShell
> v run .\src\main.v
Hello from v lang!
```

</details>

It looks like Rust and Go. 😀
