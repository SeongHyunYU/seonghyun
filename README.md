#include <stdio.h>

int main()
{

	printf("------ Made by[유 성 현] --------[2017038042]\n");
	char charType;
	int integerType;
	float floatType;
	double doubleType;

	printf("Size of char: %ld byte\n",sizeof(charType)); // 선언된 변수charType 의 자료형이 char 이기때문에 1이 찍히게된다.
	printf("Size of int: %ld byte\n",sizeof(integerType)); // 선언된 변수 integertype 의 자료형이 int 이기때문에 4가 찍히게된다.
	printf("Size of float: %ld byte\n",sizeof(floatType)); // 선언된 변수 floatType 의 자료형이 float 이기때문에 4가 찍히게된다.
	printf("Size of double: %ld byte\n",sizeof(doubleType)); // 선언된 변수 doubleType 의 자료형이 double 이기때문에 8이 찍히게된다.

	printf("----------------------------------------\n");

	printf("Size of char: %ld byte\n",sizeof(char)); // char 자료형의 크기 즉 1이 찍힌다.
	printf("Size of int: %ld byte\n",sizeof(int)); // int 자료형의 크기 즉 4가 찍힌다.
	printf("Size of float: %ld byte\n",sizeof(float)); // float 자료형의 크기 즉 4가 찍힌다.
	printf("Size of double: %ld byte\n",sizeof(double)); // double 자료형의 크기 즉81이 찍힌다.

	printf("----------------------------------------\n");

	printf("Size of char*: %ld byte\n",sizeof(char*)); // 포인터형은 자료형과 상관없이 4바이트를 할당한다.
	printf("Size of int*: %ld byte\n",sizeof(int*)); // 포인터형은 자료형과 상관없이 4바이트를 할당한다.
	printf("Size of float*: %ld byte\n",sizeof(float*)); // 포인터형은 자료형과 상관없이 4바이트를 할당한다.
	printf("Size of double*: %ld byte\n",sizeof(double*)); // 포인터형은 자료형과 상관없이 4바이트를 할당한다.

	return 0;



}
