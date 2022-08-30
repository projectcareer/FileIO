# FileIO
.NET 文件系统，可在 System.IO 命名空间引用中实现其功能。
	1. System.IO命名空间
		a. get和set文件和目录的属性
		b. Directory类公开用于创建、移动以及枚举目录和子目录的静态方法
	2. 列出所有目录
		a. Direcotry.EnumerateDirectories(目录）
	3. 列出目录中的文件
		a. Directory.EnumerateFiles(目录)
	4. 列出目录和子目录中的所有内容
		a. Directory.EnumerateDirectories 和 Directory.EnumerateFiles 函数都具有一个重载，该重载接受用于指定搜索模式文件和目录必须匹配的参数。它们还具有另一个重载，该重载接受用于指示是否以递归方式遍历指定的文件夹及其所有子文件夹的参数。
		b. Directory.EnumerateFiles(目录，"*.txt",SearchOption.AllDirectories)
	
