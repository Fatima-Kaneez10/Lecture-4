# Lecture-4
//exercise input from user-age
#include <iostream>
using namespace std;
int main()
{
	cout << "Enter Your Age: ";
	int age;
	cin >> age;
	cout << "Your age is: " << age << endl;
	return 0;
}
  
  
  
  
  //exercise mathematical operators
#include <iostream>
using namespace std;
int main()
{
	int a = 5;
	int b = 10;
	int c = a + b;
	cout << "sum of 2 number is :" << c << endl;
	return 0;
}



//exercise declare the data type
#include <iostream> 
using namespace std;
int main() {
	int firstNumber = 1;
	bool iCanCode = true;
	char hopefulGrade = 'a';
	double myDecimal = 1.0;
	string minimalSentance = "y";
	int keyMash = 13213123;
	float mysteryDataType = 5.6f;
	return 0;
}

	
	
	//exercise division fix
#include <iostream>
using namespace std;
int main() {
	int numberOne = 50;
	int numberTwo = 7;
	cout << numberOne / numberTwo << endl;
	return 0;
}

	
	
	
	//exercise untidy code
#include <iostream> 
#include <string> 
using namespace std;
int main() {
	cout << "This is untidy code.";
	cout << "I'm surprised it works.";
	int number = 6;
	cout << "It has" <<number << "lines of code - ";
	cout << "each more hideous than the last. ";
	cout << "You probably should add some line breaks in the text too" << endl;
	return 0;
}

	
	
	//exercise usb sticks
#include <iostream>
using namespace std;

int main()
{

	int money = 50;
	int price_eachUsbStick = 06;
	int USB_sticks = 50 / 6;
	int Reminder = 50 % 6;

	cout << "[Divide 50 by 6 and write quationt and reminder]" << endl;
	cout << "Quationt:" << USB_sticks << endl;
	cout << "reminder:" << Reminder << endl;

	return 0;
}
