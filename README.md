#define _CRT_SECURE_NO_WARNINGS
#include <stdlib.h>
#include <stdio.h>

int WORTH(int num1, int num2, int num3, int num4)
{
	if ((num1 * num2) == (num3 + num4))
		return 1;
	else
		return 0;


}

void main()
{
	int num1, num2, num3, num4, answer;
	printf("gimme 4 numbers pls\n");
	scanf("%d %d %d %d", &num1, &num2, &num3, &num4);

	answer = WORTH(num1, num2, num3, num4);
	printf("%d", answer);

}
