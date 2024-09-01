#include <iostream>
#include <string.h>
#include <cstdlib>

using namespace std;

void fullFill_dreams();

int main(){
	
	bool iDidIt = false;
  	string yes_No;
  	
  	do{
  		cout << "Did you manage to fulfill your dreams? ";
  		cin >> yes_No;
  	
  		if(yes_No == "Yes"){
  			iDidIt = true;
  		} else if(yes_No == "No"){
  			cout << "Try again until you did it :)";
  			cout << "\n\n";
  		}
  	} while(yes_No == "No");
  	
  	if(iDidIt == true){
  		fullFill_dreams();
  	}
}

void fullFill_dreams(){
	cout << "\n";
	cout << "Congratulations! Im so proud of you... :)";
}

/*
There's literally nothing to show. 
But I'll fill this space when my 
dreams were done, although at the 
moment I will work on them to feel 
satisfied...
*/
