#include<iostream>
using namespace std;

void flowerShop(int redRose , int whiteRose , int tulip)
{
    int red_price = 2 * redRose;
    float white_price = 4.1 * whiteRose;
    float tulip_price = 2.5 * tulip;
    float total_price = red_price+white_price+tulip_price;

    cout<<"Original price: $"<<total_price<<endl;
    if(total_price>=200)
    {
        float discounted_value = total_price*20/100;
        float actual_value = total_price-discounted_value;

        cout<<"Price after Discount: $"<<actual_value<<endl;
    }
    if(total_price<200)
    {
        cout<<"No discount applied."<<endl;
    }

}
main()
{
    int red , white , tulips;
    cout<<"Red Rose: ";cin>>red;
    cout<<"White Rose: ";cin>>white;
    cout<<"Tulips: ";cin>>tulips;

   flowerShop(red , white , tulips);
    
}