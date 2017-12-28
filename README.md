# mkjpg
Auto make function call relationship in JPG picture!

[参考资料](https://www.ibm.com/developerworks/cn/linux/l-graphvis/)

## Precondition
+ gcc
+ graphviz
## Installation
	git clone git@github.com:peiyake/mkjpg.git
	cd mkjpg
	make
	make install

## Usage
	mkjpg <c source file>
	e.g:mkjpg demo.c
Then it will create demo.jpg about the function call relationship of your c source file!
