# C-with-hackerrank
// program with for loop
#include <iostream>
#include <cstdio>
using namespace std;

int main()
 {
    // Complete the code
    int n1,n2;
    cin>> n1>>n2;
    string Arr1[9] ={"one", "two" ,"three" , "four" ,"five", "six", "seven", "eight", "nine"};
    for(int i =n1; i <=n2; i++){
        if(i<=9) 
        {cout<< Arr1[i-1]<<endl;}
        else { 
            if( i%2 ==0)
        {cout<< "even"<< endl;}
        
        else {
         cout<<"odd" <<endl; 
        }}}
    return 0;
}
 
