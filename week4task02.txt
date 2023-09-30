#include<iostream>
using namespace std;

void TrueOrFalse(string condition)
{
    
    if(condition=="true")

    cout<<"false";

    if(condition=="false")
    {
        cout<<"true";
    }
}

main()
{
    cout<<"Enter 'true' or 'false': ";
    string condition ; cin>>condition;

    TrueOrFalse(condition);
}