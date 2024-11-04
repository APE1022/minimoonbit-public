统一包查询平台：[mooncakes.io: MoonBit pacakge registry](https://mooncakes.io/)

#### 1.更新索引（当作习惯
于终端输入以下指令
```
moon update
```

#### 2.添加模块依赖
通过指令或手动编辑
```
moon add <作者名>/<模组名>
```

or
在moon.mod.json中修改deps字段

#### 3.导入模块中的包
于配置文件`moon.pkg.json`，在`import`字段声明这个包中需要导入的包。（即导入阶段）
```
{
  "is_main": true,
  "import": [
    { "path": "Yoorkin/example/list", "alias": "ls" }
  ]
}
```

4.移除依赖的模块
```
moon remove <作者名>/<模组名>
```