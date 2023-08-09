
#include <stdio.h>
int main()
{
	int arr1size=5 , arr2size=5 , arr_resultsize, i, j;
	
	int a[arr1size];
	printf("Enter the elements for first array :");
	for( int i=0;i<arr1size;i++)
	{
		scanf("%d",&a[i]);
	}
	for (i = 0; i < arr1size; i++) {
		printf("%d, ", a[i]);
	}
	int b[arr2size];
	printf("Enter the elements for second array :");
	for( int i=0;i<arr2size;i++)
	{
		scanf("%d",&b[i]);
	}
	for (i = 0; i < arr2size; i++) {
		printf("%d, ", b[i]);
	}
	arr_resultsize = arr1size + arr2size;
	int c[arr_resultsize];

	for (i = 0; i < arr1size; i++) {
		c[i] = a[i];
	}

	for (i=0, j = arr1size;i<arr2size,
		j < arr_resultsize ;i++,  j++) {
		c[j] = b[i];
	}

	for (i = 0; i < arr_resultsize; i++) {
		printf("%d, ", c[i]);
	}
	printf("\n");
	return 0;
}	
