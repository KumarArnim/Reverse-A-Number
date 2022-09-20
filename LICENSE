#include<iostream>
using namespace std;
int main(){
    int a;
    cout << "Enter the number you want to reverse :" << endl;
    cin >> a;
    int num = 0;
    while(a != 0){
        int digit = a % 10;
        if(num >= (INT_MIN/10)  || num <= (INT_MAX/10)){
            num = (10 * num) + digit;
            }
        else return 0;
        a = a / 10;
        }
    cout << "The reversed number is : " << num << endl;
    }
