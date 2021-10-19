#include <iostream>  
#include <stdlib.h>  

using namespace std;  
int main() {
	int h=0,m=0,s=0,sanie=0;    
  	cout<<"chand sanie ? ";
	cin>>sanie;
	h+=(sanie/60)/60;
	m+=(sanie-(3600*h))/60;
	s+=sanie-((3600*h)+(m*60));
	cout<<h<<" : "<<m<<" : "<<s<<endl;
return 0;
}