# Iterate-through-a-word
#For loop
#include<iostream>
#include<string>
using namespace std;
int main()
{
	for (int i = 0; i < 5; i++)
	{
		string myWord = "CRASH";
		cout << myWord.at(i) << endl;
	}
	return 0;
}
