#include<iostream>
#include<math.h>
using namespace std;
double Sumofseries(double a, double n)
{
    double sum = 0;
    for(double i=1;i<=n;++i)
    {
     sum+=(i/pow(a,i));
    }
return sum;
}
int main ()
{
double a,n;
cout<<"enter the values of a: ";
cin>>a;
cout<<"enter the values of n: ";
cin>>n;
cout<<(Sumofseries(a,n));
return 0;
}
