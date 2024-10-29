# List of used functions
1. [strtoul()](https://www.runoob.com/cprogramming/c-function-strtoul.html) from ```<stdlib.h>``` 
```C++
unsigned long int strtoul(const char *str, char **endptr, int base)
```
- **str**: A pointer to the null-terminated string to be converted.
- **endptr**: A pointer to a pointer to character, which will be set to the character after the last character used in the conversion.
- **base**: The base of number system to be used for conversion. It can be any value between 2 and 36, or 0 for auto-detection.
- **return Value** The function returns the converted unsigned long integer value. If no valid conversion could be performed, it returns 0. If the value is out of the range of representable values, it returns ```ULONG_MAX``` and sets ```errno``` to ```ERENGE```