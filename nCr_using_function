#include<iostream>
using namespace std;
//int factorial(int n)
int fact(int n)
{
	int fact=1;          //you can use write variable name and fuction name same.
	for(int i=1;i<=n;i++)
	{
		fact=fact*i;
	}
	return fact;
}
int nCr(int n, int r)
{
	//int num=factorial(n);
	int num=fact(n);
	//int demon=factorial(r)*factorial(n-r);
	int denom=fact(r)*fact(n-r);
	//return num/demon;
	int ans=num/denom;
	return ans;
}

int main()
{
	int n,r;
	cout<<"enter the value of n:-"<<endl;
	cin>>n;
	cout<<"enter the value of r:-"<<endl;
	cin>>r;
	//nCr(n,r);
	cout<<nCr(n,r);
return 0;
}
