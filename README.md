# Lab-5
Zaid's Lab 5
//Zaid's Programme Lab 5
#include <iostream>
#include <string>
using namespace std;


int main()
{
  string name;
 cout << "What is your name? ";
  getline (cin, name);
  cout << "Hello, " << name << "!\n";
  
  cout<< "Enter a POSITVE Value of X and Z  ";
  int x,z;
  cin>> x  >>z;
  
   if((x>=0) && (z>=0))
   {
       cout<<"Excellent.";
   }
    else
   { 
       cout<<"Positive Values For Both X and Z Please.";
   }
   
   return 0;
}
