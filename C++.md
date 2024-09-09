C++ Note!
=========
紀錄C++實用小東西!





puts()
------
>Declartaion:
>```C++
>int puts(const char* str);
>```
>
>Function:
>C / C ++中的puts()函數用於將一行或字串寫入output（ ）流stdout。 它用換行符列印傳遞的字串，並返回一個整數值。
>
>Example:
>```C++
>#include<stdio.h>
>int main()
>{
>	//string initialisation
>    char Mystr[] = "C and C++";
>    
>    puts(Mystr); //writing the string to stdout
>    
>    return 0;
>}
>```
>
>Output:
>```C++
>C and C++
>```

Pointer vs Reference
------
>| 特性 | 指針（Pointer） | 引用（Reference） |
>| :----: | :----: | :----: |
>|定義	|存儲一個變量的地址	|另一個變量的別名
>|初始化	|可以未初始化，且可以隨時改變指向的對象	|必須在定義時初始化，且不能更改綁定
>|空值	|可以是 nullptr 表示不指向任何對象	|不存在空引用，必須綁定到一個變量
>|重新綁定	|可以改變指向的對象	|不能改變引用所綁定的對象
>|使用情況	|常用於動態內存、數組遍歷、函數指針等	|常用於參數傳遞、避免拷貝、返回大對象等
>|操作	|需要使用 * 和 & 來解引用和取地址	|可以像正常變量一樣使用
>|內存占用	|指針是一個變量，占用內存來存儲地址	|引用不占用額外內存，它只是別名
