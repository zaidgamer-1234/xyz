#include<iostream>
using namespace std;

void discount(string country, double ticketPrice)
{    
    double priceAfterDiscount; 
    
    if(country == "Pakistan")
    {   
        priceAfterDiscount = 0.95 * ticketPrice;
        cout << "Final ticket price after discount: $" << priceAfterDiscount;
    }
    if(country == "Ireland") 
    {
        priceAfterDiscount = 0.9 * ticketPrice;
        cout << "Final ticket price after discount: $" << priceAfterDiscount;
    }
    if(country == "India")
    {
        priceAfterDiscount = 0.8 * ticketPrice;
        cout << "Final ticket price after discount: $" << priceAfterDiscount;
    }
    if(country == "England")
    {
        priceAfterDiscount = 0.7 * ticketPrice;
        cout << "Final ticket price after discount: $" << priceAfterDiscount;
    }
    if(country == "Canada")
    {
        priceAfterDiscount = 0.55 * ticketPrice;
        cout << "Final ticket price after discount: $" << priceAfterDiscount;
    }
    
}

int main() 
{
    string name; 
    double ticketPrice;
    cout << "Enter the country's name: ";
    cin >> name;
    cout << "Enter the ticket price in dollars: $";
    cin >> ticketPrice;

    discount(name, ticketPrice);

  
}
