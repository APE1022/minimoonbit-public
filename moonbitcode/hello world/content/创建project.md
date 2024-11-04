### 创建project
1.于终端输入指令并填写信息(选择exec)
```
moon new
```

创建如下文件形式
```
my-project
├── LICENSE
├── moon.mod.json
├── README.md
└── src
    ├── lib
    │   ├── hello.mbt
    │   ├── hello_test.mbt
    │   └── moon.pkg.json
    └── main
        ├── main.mbt
        └── moon.pkg.json

```

运行程序 
```
moon run src/main
```