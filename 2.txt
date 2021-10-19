#include <iostream>  
#include <stdlib.h>  

using namespace std;  
int main() {
	int h=0,m=0,s=0,sanie=0;    
  	cout<<"[";
	cin>>h;
		system ("CLS");
	cout<<"["<<h<<"] : [";
	cin>>m;
		system ("CLS");
	cout<<"["<<h<<"] : ["<<m<<"] : [";
	cin>>s;
		system ("CLS");
	cout<<"["<<h<<"] : ["<<m<<"] : ["<<s<<"]"<<endl;
	
	sanie+=(h*60)*60;
	sanie+=(m*60);
	sanie+=s;
	cout<<h<<" : "<<m<<" : "<<s<<" = "<<sanie<<" sanie ast."<<endl;
return 0;
}