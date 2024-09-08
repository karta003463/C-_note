C++ Note!
=========






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