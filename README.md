# Lab-5.30
#include <iostream>
#include <iomanip>
using namespace std;

int main() {
double m;
double y2;
double y1;
double x2;
double x1;
double y;
double c;
double x;

cout << setprecision(2) << fixed;	

cout << "Enter x1\n";
cin >> x1;
cout << "Enter y1\n";
cin >> y1;
cout << "Enter x2\n";
cin >> x2;
cout << "Enter y2\n";
cin >> y2;

m = (y2-y1)/(x2-x1);
cout << "The slope of the line is: " << m << endl;

c = y1 - m * x1;

cout << "y = " << m << "x + " << c << endl;

  
}
