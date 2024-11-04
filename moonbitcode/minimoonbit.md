#### 1.对不同文件的函数的调用

1)存在于lib文件夹下的hello.mbt文件下的函数：
```
pub fn hello() -> String {
  "Hello, world!"
}
```
2)src文件下main对别的文件的函数的调用见[[访问控制]]
```
fn main {//程序的入口，在初始化后进行
  println(@lib.hello())
  }
```
3).json文件下对调用函数所在文件的地址的记录
```
{

  "is-main": true,

  "import": [

    "TimFUNG/test_packages/lib",

    "Yoorkin/example/list"

  ]

}
```

### 2.Argparser包的引入 (见[[Moonbit 包管理]])
[Yoorkin/ArgParser: command line argument parser for MoonBit](https://github.com/Yoorkin/ArgParser)

首先在进行moon update后再进行add
注意名字是Yoorkin/ArgParser
会自动下载另外的包