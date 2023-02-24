#include<iostream>
using namespace std;
void altswap(int arr[],int size)
{
	for(int i=0;i<size;i+=2)
	{
		if(i+1<size)
		{
			swap(arr[i],arr[i+1]);
		}
	}
}
void printaltswap(int arr[],int size)
{
	for(int i=0;i<size;i++)
	{
		cout<<arr[i];
	}
	cout<<endl;
}
int main()
{
	int size;
	cout<<"enter the size of array"<<endl;
	cin>>size;
	int arr[100];
	cout<<"the value in array"<<endl;
	for(int i=0;i<size;i++)
	{
		cin>>arr[i];
	}
	altswap(arr,size);
	//altswap(brr,size);
	printaltswap(arr,size);
	//printaltswap(brr,size);
return 0;
}
