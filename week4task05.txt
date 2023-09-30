#include<iostream>
using namespace std;

void dice(int p1 , int p2)
{
    if(p2-p1 > 6)
    {
        cout<<"false";
    }
    if(p2-p1 <=6)
    {
        cout<<"true";
    }

}


int main()
    {int p1,p2;
        cout<<"Enter your position: ";cin>>p1;
        cout<<"Enter your friend's position: ";cin>>p2;
        dice(p1,p2);
    }