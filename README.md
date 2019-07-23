# -
	# Go语言的基本类型有：
		bool
		string
		int、int8、int16、int32、int64
		uint、uint8、uint16、uint32、uint64、uintptr
		byte // uint8 的别名
		rune // int32 的别名 代表一个 Unicode 码
		float32、float64
		complex64、complex128

	# 定义变量
	 > var 定义 var 变量名 变量类型   <当一个变量被声明之后，系统自动赋予它该类型的零值,所有的内存在 Go 中都是经过初始化的>
		int 为 0，
			float 为 0.0，
			bool 为 false，
			string 为空字符串，
			指针为 nil 等。
		2) := <简短格式> 注 : 定义变量，同时显式初始化; 不能提供数据类; 只能用在函数内部
