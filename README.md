#include <iostream>
using namespace std ;
int main()
{
	char pq;
	int num1,num2;
	cout<<"enter an operator:+,-,*,/,%,";
	cin>>pq;
	cout<<"enter two numbers:";
	cin>>num1>>num2;
	switch(pq)
	{
	case '+':
		cout<<num1<<"+"<<num2<<"="<<num1+num2;
		break;
	case '-':
		cout<<num1<<"-"<<num2<<"="<<num1-num2;
		break;
	case '*':
		cout<<num1<<"*"<<num2<<"="<<num1*num2;
		break;
	case '/':
		cout<<num1<<"/"<<num2<<"="<<num1/num2;
		break;
	case '%' :
		cout<<num1<<"%"<<num2<<"="<<num1%num2;
		break;
 default:cout<<"operator is incorrect ";
 break;
	}
	return 0;
}