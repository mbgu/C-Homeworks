/*Write a program in C++ that calculates 
the addition, subtraction, multiplication or
division of any two numbers using a function 
(the user can choose the operator).*/
#include<iostream>
using namespace std;
float addFun(float, float);
float subFun(float, float);
float mulFun(float, float);
float divFun(float, float);
int main()
{
    float num1, num2;
    char oper;
    cout<<"Enter Two Numbers: ";
    cin>>num1>>num2;//reads two float numbers from inputs 
    cout<<"Enter the Operator (+, -, *, /): ";
    cin>>oper;//reads single character (the operator) from the input and stores it in the variable oper.
    if(oper=='+')
        cout<<endl<<"Addition is = "<<addFun(num1, num2);
    else if(oper=='-')
        cout<<endl<<"Subtraction is = "<<subFun(num1, num2);
    else if(oper=='*')
        cout<<endl<<"Multiplication is = "<<mulFun(num1, num2);
    else if(oper=='/')
        cout<<endl<<"Division is = "<<divFun(num1, num2);
    else
        cout<<endl<<"Please write a operator addition, subtraction, multiplication, or division such as + - / *";
    cout<<endl;
    return 0;
}
float addFun(float x, float y)
{
    return x+y;
}
float subFun(float x, float y)
{
    return x-y;
}
float mulFun(float x, float y)
{
    return x*y;
}
float divFun(float x, float y)
{
    return x/y;
}
