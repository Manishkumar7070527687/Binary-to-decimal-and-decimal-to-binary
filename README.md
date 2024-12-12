//# Binary-to-decimal-and-decimal-to-binary

#include<iostream>
using namespace std;
int main(){
      int n;
      cin>>n;
      int ans=0;
      int power=1;
                             //isi code me hm bin to dec kr skte h  
      while(n>0){
        int x= n % 2;
        ans += power*x;
        power *=10;
        n /=2;
      }  
      cout<<ans;


    return 0;
} 


#include<iostream>
using namespace std;
int main(){
      int n;
      cin>>n;
      int ans=0;
      int power=1;
                             //isi cod me dec to bin kr skte h 
      while(n>0){
        int x= n % 10;
        ans += power*x;
        power *=2;
        n /=10;
      }  
      cout<<ans;


    return 0;
} 

