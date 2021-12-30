# calculator
my first repository
#include <iostream>
using namespace std;
int main(){
	
	float a;
	cout<<"enter first no"<<endl;
	cin>>a;
	
	float b;
	cout<<"enter second no"<<endl;
	cin>>b;
	
	float sum,sub,mul,div;
	sum=a+b;
	sub=a-b;
	mul=a*b;
	div=a/b;
	
	int choice;
	cout<<"choose sum=1,sub=2,mul=3,div=4,mod=5"<<endl;
	cin>>choice;
	
	if (choice==1)
	{
		
		cout<<"sum"<<sum;
		
}
	if (choice==2)
	{
		
		cout<<"subtraction"<<sub;
		
}
	if (choice==3)
	{
		
		cout<<"multiplication"<<mul;
		
}
	if (choice==4)
	{
		
		cout<<"division"<<div;
		
}
    return 0;
}
