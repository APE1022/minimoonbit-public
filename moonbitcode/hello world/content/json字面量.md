#### json字面量
	what：- JSON 指的是 JavaScript 对象表示法（Java Script Object Notation），轻量级的文本数据交换格式

MoonBit 通过重载字面量的形式支持 json 字面量，能够便捷地创建和操作 json 数据。当预期类型是 `@json.JsonValue` 时，数字、字符串、数组和 `Map` 字面量可以被用于创建 json 数据：