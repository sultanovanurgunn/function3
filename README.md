# function3
#include <iostream>
using namespace std;
void swapNumbers(double a,double b){
 a=a+b;
 b=a-b;
 a=a-b;
}
 int main(){
     int a,b;
     cout<<"iki eded daxil edin"<<endl;
     cin>>a>>b;
     
    swapNumbers(a,b);
    return 0;
}
