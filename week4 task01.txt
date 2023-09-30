#include<iostream>
using namespace std;

void integers(int n1 , int n2)
{
    if(n1 ==  n2)
    {
        cout<<"true";
        
    }

    if(n1 > n2 ||  n1 < n2)
    {
        cout<<"false";
    }

}

main()
{
    
    
        
    int n1 ; int n2;
    cout<<"Enter the first number: ";cin>>n1;
    cout<<"Enter the second number: ";cin>>n2;

    integers(n1 , n2);

    
}