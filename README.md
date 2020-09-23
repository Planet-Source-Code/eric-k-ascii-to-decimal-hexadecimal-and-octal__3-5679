<div align="center">

## ASCII to Decimal, Hexadecimal, and Octal


</div>

### Description

This program will convert ASCII to decimal, hexadecimal, and octal.
 
### More Info
 
I am a beginner C/C++ coder so the code is probably messy and disorganized. Any feedback/suggestions is welcomed!


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Eric K](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/eric-k.md)
**Level**          |Beginner
**User Rating**    |4.0 (24 globes from 6 users)
**Compatibility**  |C, Microsoft Visual C\+\+
**Category**       |[Strings](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/strings__3-26.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/eric-k-ascii-to-decimal-hexadecimal-and-octal__3-5679/archive/master.zip)





### Source Code

```
#include <stdio.h>
#include <stdlib.h>
#include <string.h>
main()
{
	char string[1024];
	int length;
	printf("ASCII Input: ");
	gets(string);
	printf("\n");
	printf("\n");
	printf("Decimal Ouput:  ");
	for(length = 0; length < strlen(string); length++)
	{
		printf("%d ", string[length]);
	}
	printf("\n");
	printf("Hexadecimal Output: ");
	for(length = 0; length < strlen(string); length++)
	{
		printf("%x ", string[length]);
	}
	printf("\n");
	printf("Octal Output:  ");
	for(length = 0; length < strlen(string); length++)
	{
		printf("%o ", string[length]);
	}
	printf("\n");
	printf("\n");
	system("pause");
	return 0;
}
```

