EXEC模块，可直接在程序中调用，VS请设置多字节字符集

仅适用于windows，正在完善中...

示例：

#include "Cmd.h"

int main() 

{
	//example

	string result;

	result = RunCommand("ping baidu.com");

	return 0;

}
