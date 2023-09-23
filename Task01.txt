#include<iostream>
using namespace std;

main() {
float degrees;
cout<<"Enter the number of sides of the polygon: ";
int sides_of_polygon;
cin>>sides_of_polygon;

int sum_of_internal_angles = (sides_of_polygon-2) * 180;

cout<<"The sum of internal angles of a " <<sides_of_polygon << "-sided polygon is: "<<sum_of_internal_angles<<" degrees" ;

}