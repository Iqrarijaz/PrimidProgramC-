# PrimidProgramC++
#include <iostream>
using namespace std;

void main()
{
	int space, rows;

	for (int i = 0; i <= 5; i++)
	{
		for (int space = 0; space < 5 - i; space++)
		{
			cout << "   ";
		}
		for (int star = 0; star < i; star++)

		{
			cout << "  *  ";
		}
		cout << endl;
	}

	system("pause");
}
