# 正则表达式 regexp

[RegExr: Learn, Build, & Test RegEx](https://regexr.com/)

[regex101: build, test, and debug regex](https://regex101.com/)

[cyrilex: test, and visualize regex](https://extendsclass.com/regex-tester.html)

## 基础正则

* `^` 开头
* `$` 结尾
* `^$` 空行
* `.` 单个字符
* `*` 前一个字符连续出现 0 次或 0 次以上
* `.*` 任意内容
* `[abc]` 匹配 a 或 b 或 c
* `[^abc]` 排除 a、排除 b、排除 c
* `[0-9]` 匹配单个数字
* `[a-z]` 匹配单个小写字母
* `[A-Z]` 匹配单个大写字母
* `[a-zA-Z]` 匹配单个字母
* `[a-zA-Z0-9]` 匹配单个字母或数字
* `[.! ]$` 匹配以 . 或 ! 或空格结尾的行（`[]` 会去掉符号的特殊含义）

## 扩展正则

* `?` 前一个字符出现 0 次或 1 次
* `+` 前一个字符连续出现 1 次或 1 次以上
* `[a-zA-Z]+` 匹配单词
* `|` 或匹配，例如 `ubuntu|debian` 匹配包含 ubuntu 或 debian 的行
* `()` 表示一个 Group，用于反向引用
* `{n,m}` 前一个字符至少出现 n 次、至多出现 m 次
* `{n}` 前一个字符刚好出现 n 次
* `{n,}` 前一个字符至少出现 n 次
* `{,m}` 前一个字符至多出现 m 次

## Perl 正则

* `\d` 匹配 `[0-9]`
* `\D` 不匹配 `[0-9]`，即 `[^0-9]`
* `\s` 匹配空字符、空格、tab、换行等
* `\S` 匹配非空字符
* `\w` 匹配 `[0-9a-zA-Z_]`
* `\W` 不匹配 `[0-9a-zA-Z_]`
