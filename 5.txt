#include <iostream>
#include <conio.h>
#include <cstdlib>
#include <ctime>
using namespace std;

int main() {
	int c=0;
		cout<<"shoro ya payan ? (enter/esc)";
	a:
	if(getch()==13){
		b:
			srand((int)time(0));
		for(;;){
			c=(rand()%6)+1;
			cout<<c<<endl;
			if(c==6){
				c=0;
				c=(rand()%6)+1;
				cout<<c<<endl;
				if(c!=6)
					break;
			}
			else
				break;
		}
	}
	else if (getch()==27){
		cout<<"khodafezi :/";
		return 0;
	}
	else{
		goto a;
	}
	cout<<"edame midi ? (enter/esc)";
	if(getch()==13){
		goto b;
	}
	if(getch()==27){
		cout<<"khodafezi :/";
	}
  
  return 0;
}