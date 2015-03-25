# lalala
#include<iostream>
using namespace std;
char compare(int a,int b)
{
  if(a>b)
    return '>';
  else
    return '<';
}
int main()
{
  int a=5,b=10;
  char ch;
  ch = compare(a,b);
  cout<<ch<<endl;
}
