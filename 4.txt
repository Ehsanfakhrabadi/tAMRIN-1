#include <iostream>
using namespace std;

int main() {
	
	int max=0,min=0,a=0,count=0,c=0;
	float avg=0;
	cout << "redad daneshjo ra vared konid : ";
	cin>>count;
	c++;
	cout<<"nomre daneshjo ["<<c<<"] : ";
	cin>>a;
	max=a;
	min=a;
	avg=a;
	for(int i=count;i>1;i--){
			c++;
			cout<<"nomre daneshjo ["<<c<<"] : ";
			cin>>a;
			avg+=a;
			if(a>max)
				max=a;
			if(a<min)
				min=a;			
	}
	avg=avg/count;
    cout << "avg = " << avg<< endl;
    cout << "Max = " << max<< endl;
    cout << "min = " << min<< endl;
  
  return 0;
}