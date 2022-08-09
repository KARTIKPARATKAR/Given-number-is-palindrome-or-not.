# Given-number-is-palindrome-or-not. #palindromenumber #palindrome #number #c++
This is the C++ program to find given number is palindrome number or not.
#include<iostream>
using namespace std;
int main()
{
 int n,r,rev=0,m;
 cout<<"give number"<<endl;
 cin>>n;
 m=n;
 while(n>0)
 {
    r=n%10;
    n=n/10;
    rev=rev*10+r;

 }
 if(rev==m)
 {
    cout<<"given number is palindrome number"<<endl;

 }
 else{
    cout<<"given number is not palindrome number"<<endl;

 }
 cout<<"reverse of a number is"<<" "<<rev<<endl;
 return 0;

}
