#include<iostream>
using namespace::std;
int main() 
{
    cout<<"hello world"<<endl;
    int a,count=0;
    cout<<"enter the number"<<endl;
    cin>>a;
    for(int i=2;i<=a;i++)
    {
        if(a%i==0)
        {
            count++;
        }
    } 
    if(count==1)
    {
       cout<<"it is a prime number";
    }  
    else
    {
        cout<<"It is not a prime number";
    }
        return 0;
}
