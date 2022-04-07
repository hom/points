# points
`rust` 中 使用 `fn` 来声明函数；而 `go` 语言中使用 `func`；`JavaScript` 中使用 `function`；`python` 中使用 `def`；`C` `C++` 中直接以返回值 `void` `int` `string` ... 来声明函数；

`rust` 中使用 `Vec` 来声明可变数组，是 `Vector` 的缩写；`C++` 中以 `Vector` 来生命可变数组；

`rust` 使用 `cfg!(debug_assertions)` 来条件编译 `debug` 模式下的输出；

`rust` `C` `C++` `Go` 语言中均使用 `"` 来代表字符串，使用单引号 `'` 来代表单个字符 `char`；在 `JavaScript` 中使用单引号 `'` 来代表字符串和单个字符 ；

`rust` 使用 `let` `var` 声明不可变变量， 使用 `let mut variable` 声明可变变量，`const` 声明常量；`Python` 中直接生命变量；`C` `C++` 中使用 `类型` + `variable` 来声明变量；`Go` 语言使用 `var` 声明变量；

`rust` 基本数据类型包括：
- 数值类型：有符号数值（`i8` `i16` `i32` `i64` `isize`），无符号数值（`u8` `u16` `u32` `u64` `usize`）
- 字符串：字符串字面量和切片 `&str`
- 布尔类型：`true` `false`
- 字符类型：单个 `char` Unicde类型存储为 `4` 个字节
- 单元类型：`()` 唯一的值也为 `()`

`rust` 使用 `panic` 抛出错误；`Go` 使用 `panic` 抛出错误；`Python` 使用 `raise` 抛出错误；`JavaScript` 使用 `throw` 抛出错误；

`rust` 中也包含有 `Nan`，使用 `is_nan` 来进行比较；

`rust` 中使用 `..` 来生成序列，[1, 5) 表示为 `1..5`，[1, 5] 表示为 `1..=5`；在 `Python` 中使用 `range` 函数来实现；

`rust` 中函数使用需要表明参数和返回值类型；无返回值时使用 `()` 表示，使用 `!` 表示函数永不返回；

`rust` 中使用 `"` 声明的字面量字符串是不可变的，如果需要声明动态字符串类型则需要使用 `String` 来实现；

`rust` 中每一个值都有且只有一个所有者（变量）

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTU1NjI2MTQzMSwxNjc0OTExMzEwLDE3ND
IyMTQxMzEsLTc1NTY2NzE1NywtMTU0MjA0ODc3NywtMTQ3MTUz
MzgzNCwxNzUxODc5MjAyLC05Mjg4NjU3MzQsMjc2OTU3ODg3XX
0=
-->