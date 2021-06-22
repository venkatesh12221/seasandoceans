#include<stdio.h>
int main()
{
	char ch;
	printf("enter any character:")
	scanf("%c", &ch );
	switch(ch)
	{
		case'a':
		case'A':
	    case'e':
		case'E':
	    case'i':
		case'I':
		case'o':
		case'O':
		case'u':
		case'U':
		printf("%c is Vowel.\n"ch);
		break;
		deafalt;
		printf("%c is not a Vowel.\n"ch);		
	}
	return 0;
}
