#include<iostream>
using namespace std;

void longestDuration(int h ,int m)
{
int hours_to_min = 60 * h;
if(hours_to_min > m)
    {
        cout<<h;
    }
    
if(hours_to_min < m)
    {
        cout<<m;
    }

}

int main()
{int hour,min;
    cout<<"Enter the number of hours: ";cin>>hour;
    cout<<"Enter the number of minutes: ";cin>>min;
    longestDuration(hour,min);
}