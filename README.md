[简体中文 README](README_zh.md)

# Synopsis
This project aims to list common identifier abbreviations to help coders write concise and easy to read code.

The identifier is arranged in multiple files with the first letter, but some similar words will be filed in
 independent files, for instance the abbreviations of object type in file "object_type.toml".
```toml
# This is a TOML document
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
You may find the file format type is [TOML](https://github.com/toml-lang/toml). The purpose of this is to facilitate the quick translation of the above
 abbreviations into data structures in a wide variety of languages in the future if needed.

If you want to check your writing for toml compliance, you can use online tools https://toml-parser.com.

# Common Abbreviation Rules
Common word abbreviation rules are as follows:
- The first few or some letters of a word, such as addr (address) and asm (assembly);
- Word syllable initials splicing, such as msg (message);
- Multiple word initials splicing, such as NASA (National Aeronautics and Space Administration);
- Remove the vowels aeiou and keep the consonants, such ad JPN (Japan), CHN (China) and ft (foot);
- A common abbreviation, such as thx (thanks).

# Get Involved
Documentation, bug reports, pull requests, and all other contributions are welcome!

# References
Some abbreviations refer to the website [ABBREVIATIONS](https://www.abbreviations.com).
