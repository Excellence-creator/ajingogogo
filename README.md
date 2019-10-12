# ajingogogo
#define _CRT_SECURE_NO_WARNINGS
#include<stdio.h>
#define SIZE 10
int main02()
{
	int arr[SIZE];
	int i;
	for (i = 0;i < SIZE;i++)
	{
		scanf("%d", &arr[i]);
	}
	int max = arr[0];
	for (i = 1;i < SIZE;i++)
	{
		if (arr[i] > max)
		{
			max = arr[i];
		}
	}
	printf("小猪中最重的体重是:%d\n", max);
	printf("小猪中最重的体重是:%d\n", i-1);
	return 0;
	//return EXIT_SUCCESS;
}
