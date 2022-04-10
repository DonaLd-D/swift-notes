## swift笔记

### 关键字

#### 与声明有关的关键字
```
class	deinit	enum	extension
func	import	init	internal
let	operator	private	protocol
public	static	struct	subscript
typealias	var
```
#### 与语句有关的关键字
```
break	case	continue	default
do	else	fallthrough	for
if	in	return	switch
where	while
```
#### 表达式和类型关键字
```
as	dynamicType	false	is
nil	self	Self	super
true	_COLUMN_	_FILE_	_FUNCTION_
_LINE_
```
#### 在特定上下文中使用的关键字
```
associativity	convenience	dynamic	didSet
final	get	infix	inout
lazy	left	mutating	none
nonmutating	optional	override	postfix
precedence	prefix	Protocol	required
right	set	Type	unowned
weak	willSet
```

### 数据类型
- Int
- UInt
- 浮点数：Float、Double
- 布尔值：Bool
- 字符串：String
- 字符：Character
- 可选类型：Optional

### 变量
- 变量名可以由字母，数字和下划线组成。
- 变量名需要以字母或下划线开始。
- Swift 是一个区分大小写的语言，所以字母大写与小写是不一样的。
- 变量名也可以使用简单的 Unicode 字符。

### 常量
- 常量使用关键字 let 来声明

### 字面量
- 所谓字面量，就是指像特定的数字，字符串或者是布尔值这样，能够直接了当地指出自己的类型并为变量进行赋值的值。

### 运算符
- 算术运算符
- 比较运算符
- 逻辑运算符
- 位运算符
- 赋值运算符
- 区间运算符
- 其他运算符

### 运算符优先级
- 指针最优，单目运算优于双目运算。如正负号。
- 先乘除（模），后加减。
- 先算术运算，后移位运算，最后位运算。请特别注意：1 << 3 + 2 & 7 等价于 (1 << (3 + 2))&7
- 逻辑运算最后计算

### 循环
- for-in
- while
- repeat...while

### 字符串
```
字符串插值是一种构建新字符串的方式，可以在其中包含常量、变量、字面量和表达式。 
插入的字符串字面量的每一项都在以反斜线为前缀的圆括号中。
```

### 字符串函数及运算符
- isEmpty
- hasPrefix(prefix: String)
- hasSuffix(suffix: String)
- Int(String)
- String.characters.count
- utf8
- utf16
- unicodeScalars
- `+`
- `+=`
- `==`
- `<`
- `!=`
```swift
import Cocoa
var varA:String = "Hello "
let varB:Character = "G"
varA.append( varB )
print("varC  =  \(varA)")
```


