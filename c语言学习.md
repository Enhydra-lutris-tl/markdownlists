# C语言相关知识

### 宏定义（define）
定义：  
将字符串，数等等替换为自定义的名称  
如下：将111替换为A
```text
#define A 1111
则：
int a[A] 等同于 int a[1111]
```
<br/>

***
### 结构体（struct）
```text
struct tag//结构体名称
{
    member-list;//成员列表
    
}variable-list;//变量列表（全局变量）
```
<br>

***
### 枚举（enum）
定义：<br>
枚举是C语言中的一种构造数据类型，它可以让数据更简单，更易读，只有几个有限的特定数据，可以使用枚举。<br>
枚举（enum）<br>
枚举是一组常量的集合，包含一组有限的特定的数据<br>
枚举语法定义格式为
```text
enum  枚举名  {枚举元素1，枚举元素2}
```
<br>

***

### 重命名关键字（typedef）
定义：  
C语言允许用户使用 typedef 关键字来定义自己习惯的数据类型名称。
```text
举例：
typedef int BOOL;//定义一个布尔类型
#define TRUE 1
#define FALSE 0
//定义好之后，就可以像使用基本类型数据一样使用它了，如下面的代码所示：
BOOL bflag=TRUE;
```