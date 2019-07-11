- 从文件中读取输入freopen("in.txt","r",stdin);
- 读取一行 getline(cin,str); str是一个string类型字符串
- 读取一个字符(包括空格、换行符等) getchar();
- scanf("%d: ",&n); n是一个整型变量
- 容器和数组以引用传入，可避免超时
- 重载运算符号
···cpp
/*
const修饰变量，使得变量具有常量属性，即在时候不能被使用
const修饰成员函数，只能读取数据成员，不能修改数据成员
const 是为了提高代码鲁棒性
*/
struct node{
    int value;
    bool operator<(const &a) const{
        return a.value < b.value;
    }
};


···

