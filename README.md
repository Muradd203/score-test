# score-test
#Murad khudiyev
#include<iostream>
using namespace std;
int main() {
	int a;
	
	cout << "enter your score";
	cin >> a;
	if (a <= 50)
	{
		cout << "F" << endl;
	}
	else if (50 < a && a <= 70)
	{
		cout << "C" << endl;
	}
	else if (70 < a && a <= 90)
	{
		cout << "B" << endl;

	}
	else if (a > 90)
	{
		cout << "A" << endl;
	}

	return 0;
}
