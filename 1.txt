#include <iostream>  
#include <conio.h>  
#include <string.h>  
 
using namespace std; 
 
int main() 
{ 
    int sum = 0; 
    int a; 
    string E; 
    while (E != "exit") 
    { 
        cout << "entrer votre numero :"; 
        cin >> a; 
        sum += a; 
        if(a == 0) 
        { 
            cout << "tapez existe si vou voulez finir\t"; 
            cin >> E; 
        } 
        
    } 
    cout << "Sum = " << sum; 
 
    return 0; 
}