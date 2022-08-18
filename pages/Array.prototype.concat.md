title:: Array.prototype.concat
alias:: concat

- # 坑
- `[].concat[1,2,3]` 返回什么？
	- undefined
	- 逗号运算符 从左到右 最后等价于 Array.prototype.concat[3]
	-