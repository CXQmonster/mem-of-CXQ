# mem-of-CXQ
#define _CRT_SECURE_NO_WARNINGS
#include<stdio.h>
//1
#define Addm(x,y)(x+y)//定义宏
#define max 120
//int main()
//{
//	int a = Addm(3, 4);
//	int* p = &a;
//	printf("%p\n", p);//指针，存放地址
//	printf("%d\n", a);//宏
//	printf("%d\n", max);//定义常量
//	return 0;
//}
//2
//int main()
//{
//	int age = 0;
//	scanf("%d", &age);
//	if (age < 16)
//	{
//		printf("未成年\n");
//	}
//	else
//	{
//		printf("成年");
//	}
//	return 0;
//}
//3
//在C语言中0表示假，非0表示真
//int main()
//{
//    if (1)
//    {
//        printf("成年");//这里打印成年
//    }
//    else
//    {
//        printf("失败");
//    }
//    return 0;
//}
//4
//int main()
//{
//    int a = 1;
//    int b = 10;
//    if (a == 1)
//    {
//        if (b == 2)
//            printf("hehe\n");
//        else
//        {
//            printf("keai\n");
//        }
//        
//    }
//    else
//    {
//        printf("haha\n");
//    }
//    return 0;
//}
//else和距离最近未匹配的if匹配
