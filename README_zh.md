[English README](README.md)

# 简介
本项目旨在列出通用标识符缩写，以帮助编码人员编写简洁易读的代码。

标识符以第一个字母排列在多个文件中，但一些类似的单词将在独立文件中归档，例如文件“object_type.toml”中的变量类型缩写。
```toml
# 这是一个 TOML 文档
[object_type]
b = ["bool"]
by = ["byte"]
c = ["char"]
s = ["string"]
f32 = ["float32"]
f64 = ["float64"]
i = ["int"]
i8 = ["int8"]
i16 = ["int16"]
i32 = ["int32"]
i64 = ["int64"]
u = ["uint"]
u8 = ["uint8"]		
u16 = ["uint16"]	
u32 = ["uint32"]		
u64 = ["uint64"]		
st = ["struct"]		
cl = ["class"]		
con = ["const"]		
ch = ["chan"]
ifc = ["interface"]
m = ["map"]	
func = ["function"]	
arr = ["array"]
v = ["vector"]
p = ["pointer"]
j = ["json"]
q = ["queue"]
stk = ["stack"]
o = ["object"]
sl = ["slice"]
```
文件使用 [TOML](https://github.com/toml-lang/toml) 格式，这样做的目的是为了将来如果有需要，可以方便快速将上述缩写转换为多种语言的数据结构。

如果你想检查你写的内容是否符合 toml 语法，你可以使用在线工具 https://toml-parser.com 校验.

# 常见缩写规则
对项目中常见的单词缩写进行观察总结，发现英文单词的缩写一般采用如下几个规则：
- 单词前几个或某几个字母，如 addr（address）和 asm（assemble）；
- 单词音节首字母拼接，如 msg（message）；
- 多个单词首字母拼接，如 NASA（National Aeronautics and Space Administration）；
- 去掉元音字母 aeiou 保留辅音字母，如 Japan 缩写为 JPN，China 缩写为 CHN，英尺 foot 缩写为 ft；
- 约定俗称的缩写词。如 thx（thanks）。

# 协同共建
欢迎提供文档、bug 报告、合并请求和所有其他贡献！

# 参考文献
其他缩写可参考网站 [abbreviations](https://www.abbreviations.com) 或 [allacronyms](https://www.allacronyms.com/)。
