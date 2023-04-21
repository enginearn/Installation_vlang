# The V Programming Language

This directory contains projects written in V.

## Installation for Windows

To install V, follow the instructions in the [V README](https://github.com/vlang/v#installing-v-from-source).

And also execute the following command to recgognize the V language commands:

[Getting Started With V](https://blog.vlang.io/getting-started-with-v/)

- Clone the V repository:

``` PowerShell
> git clone https://github.com/vlang/v.git
```

- Then, run the following command to build V:

``` PowerShell
> cd path/to/v
> .\make.bat
```

- Finally, run the following command to create a symlink to the V executable:

``` PowerShell
# Run this command as an Administrator.
> .\v.exe symlink
```

- After that, you can run the following command to check if V is installed correctly:

``` PowerShell
> v version
V 0.3.3 b6ecd63
```

## upgrade

``` PowerShell
installation_v> where.exe v
C:\Users\path\to\AppData\Local\v\.bin\v.bat
PS C:\Users\path\to\Development\vlang\installation_v> cd C:\Users\path\to\AppData\Local\v
PS C:\Users\path\to\AppData\Local\v>
PS C:\Users\path\to\AppData\Local\v> git pull
remote: Enumerating objects: 998, done.
remote: Counting objects: 100% (832/832), done.
remote: Compressing objects: 100% (403/403), done.
Receiving objects: 100% (998/998), 962.75 KiB | 3.40 MiB/s, done.
Resolving deltas:  74% (412/556)eused 649 (delta 417), pack-reused 166Resolving deltas:  32% (178/556)
Resolving deltas: 100% (556/556), completed with 177 local objects.
From https://github.com/vlang/v
   b6ecd634e3..72cbca9653  master           -> origin/master
 * [new branch]            l1mey112-patch-1 -> origin/l1mey112-patch-1
 * [new branch]            l1mey112-patch-2 -> origin/l1mey112-patch-2
 * [new branch]            update-gg-sokol-linux-dependencies -> origin/update-gg-sokol-linux-dependencies
 * [new tag]               weekly.2023.08   -> weekly.2023.08
 * [new tag]               weekly.2023.09   -> weekly.2023.09
Updating b6ecd634e3..72cbca9653
Fast-forward
 .github/workflows/bootstrapping_works_ci.yml       |    4 +-
 create mode 100644 vlib/v/tests/var_option_sumtype_test.v
PS C:\Users\path\to\AppData\Local\v> v version
V 0.3.3 b6ecd63
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
