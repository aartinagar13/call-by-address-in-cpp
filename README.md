# call-by-address-in-cpp

#include<iostream>
#include<conio.h>
using namespace std; 

void swappointer(int *a, int *b) {
   int temp =*a; 
   *a=*b;
   *b=temp;
}
  
int main(){
int a=4,b=5;
cout<<"before swapping the value of a is "<< a<<"and the value of b is "<<b<<endl; 
swappointer(&a,&b);
cout<<" after swapping the value of a is"<<a<<"and the value of b is"<<b<<endl;
return 0;
}




  


