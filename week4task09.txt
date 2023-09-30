#include<iostream>
using namespace std;
 void tpChecker(int people , int tp)
 {
    int avg_sheets_day = people*57;
    int total_sheets = tp*500;
    int remaing_days = total_sheets/avg_sheets_day;
    
    if(remaing_days < 14)
    {
        cout<<"Your TP will only last " << remaing_days << " days, buy more!";
    }

    if(remaing_days >= 14)
    {
        cout<<"Your TP will last " << remaing_days << " days, no need to panic!";
    }

 }

 main()
 {
    int people , tp;
    cout<<"Number of people in the household: ";cin>>people;
    cout<<"Number of rolls of TP: ";cin>>tp;
    tpChecker(people,tp);
 }
