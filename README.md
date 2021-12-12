#include<iostream>
using namespace std;
string greetings (int time)
{
if (time<12){
return " Good Morning.Have A Nice Day!";
}
else{
return "Good Afternoon.Hope You Are Having A Nice Day !";
   }
}
int main()
{
int userInput;
cout<<"What time is it?"<<endl;
cin>>userInput;
cout<<greetings (userInput)<<endl;
return 0 ;
}
