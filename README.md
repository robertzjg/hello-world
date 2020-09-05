# hello-world
//20200827 first day study C 
//#define 定义的标识符常量
//enum sex
//{
//	male,
//	female,
//	secret
//};
MAX(int x, int y)
{
	if (x > y)
		return x;
	else
		return y;
}
int main()
{

	int num1 = 10;
	int num2 = 20;
	int max = 0;
	max=MAX(num1, num2);
	printf("%d\n",max);

	return 0;
}
