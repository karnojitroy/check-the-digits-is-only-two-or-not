# check the input is only is only two digits or not

###### include<iostream>

###### using namespace std;
###### int main()
###### {
######  int num, totalDigits=0, totalIn=0;
######   do{
######   cout<<"Sample Input "<<totalIn+1<<": ";
######   cin>>num;
######   if(num>0)
######   {
######    totalIn++;
######     while(num>0){
######      totalDigits++;
######     num = num/10;
######     }
######     if(totalDigits==2){
######     cout<<"\nSample Output "<<totalIn<<": "<<totalDigits<<"Yes";
######     cout<<endl;
######     }
######     else{
######         cout<<"\nSample Output "<<totalIn<<": "<<totalDigits<<"No";
######           cout<<endl;
######     }

######   }
######   else{
######     totalIn++;
######    cout<<"The input should be grater than 0!";
######     cout<<endl;
######   }
   
###### } while(totalIn !=10001);
######   return 0;
###### }
