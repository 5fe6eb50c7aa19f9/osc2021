# My OSC 2021

## Author

| 學號 | GitHub 帳號 | 姓名 | Email |
| --- | ----------- | --- | --- |
|`309551069`| `5fe6eb50c7aa19f9` | `洪佳賢` | 51sf1hgd[at]gmail.com |

## How to build

`make`

## How to run

`make run`

## How to burn it into pi3

`dd if=<bootable image> of=<device>`

## Architecture

`raspi3 & ARM64`

## Directory structure

```
etc : bootable images
lab0: Environment Setup
lab1: Hello World
lab2: Booting
lab3: Allocator
lab4: Exception and Interrupt
lab5: Thread and User Process
lab6: Virtual File System
lab7: File System Meets Hardware
lab8: Virtual Memory
test: load kernel images through UART
```
Note: "allocator.c" bug in lab3~7 should be fixed like [this](https://github.com/5fe6eb50c7aa19f9/osc2021/commit/79247a5deac6a71291aea3e32e859e7b60b9c6b6#diff-31bc1c4fe8a5f13a3f69fb892b84587e3be0c7069e3455e3b14d7a5480ac59b9).

## Ref
https://grasslab.github.io/NYCU_Operating_System_Capstone/index.html
