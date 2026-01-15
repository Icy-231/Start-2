#include<stdio.h>
int main()
{
	int N,i,num;
	int sum=0,average=0,max=0,min=0;
	int  a = 0,Total=0;

	printf("您想输入几个数呢\n");
	scanf_s("%d",&N);


	for (i = 1; i < N + 1; i++) {
		do {
			printf("请输入第%d个数\n", i);
			scanf_s("%d", &num);
			if (num % 2 != 0 && num % 3 != 0) {
				Total++;
				sum += num;
				if (num > max)
					max = num;
				if (num < min)
					min = num;
					
			}while ();

		}
	}printf("total=%d,sum=%d,average=%d,max=%d,min=%d", Total, sum, average, max, min);
	
	
return 0;
}
