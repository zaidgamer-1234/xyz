#include<iostream>
using namespace std;

void pet(int holidays)
{
    int daysInYear = 365 ;
    int workingDays = daysInYear - holidays;
    int WorkingDaysmins = 63;
    int HolidaysMins = 127;
    int totalPlaytime = (workingDays * WorkingDaysmins) + (holidays * HolidaysMins);
    int norm = 30000;

    if(totalPlaytime<norm)
    {
        cout<<"Tom sleeps well"<<endl;

        int difference =  norm - totalPlaytime;

        int hours = difference / 60;
        int mins =  difference % 60;

        cout<<hours<<" hours and "<<mins<<" minutes less for play";


    }

    if(totalPlaytime>norm)
    {
        cout<<"Tom will run away"<<endl;
         int difference =  totalPlaytime - norm;
        int hours = difference / 60;
        int mins =  difference % 60;

        cout<<hours<<" hours and "<<mins<<" minutes for play";


    }
}


    


main()
{
    int holidays;
    cout<<"Holidays: ";cin>>holidays;
    pet(holidays);
}