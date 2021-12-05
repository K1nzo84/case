#include <iostream>
using namespace std;
int main()
{
cout << "За какой месяц вам посчитать сумму с начисленными %?" << "\n";
	cout << "\n\n";
		cout << "1-январь" << "\n";
		cout << "2-февраль" << "\n";
		cout << "3-март" << "\n";
		cout << "4-апрель" << "\n";
		cout << "5-май" << "\n";
		cout << "6-июнь" << "\n";
		cout << "7-июль" << "\n";
		cout << "8-август" << "\n";
		cout << "9-сентябрь" << "\n";
		cout << "10-овтябрь" << "\n";
		cout << "11-ноябрь" << "\n";
		cout << "12-декабрь" << "\n";
		cin >> meciyac;
		cout << "\n\n";

		switch (meciyac)

		{

		case 1:
		{
			itog1 = dollars * massiv[0];
			cout << itog1;
			break;
		}

		case 2:
		{
			itog2 = dollars * massiv[1];
			cout << itog2;
			break;
		}

		case 3:
		{
			itog3 = dollars * massiv[2];
			cout << itog3;
			break;
		}

		case 4:
		{
			itog4 = dollars * massiv[3];
			cout << itog4;
			break;
		}

		case 5:
		{
			itog5 = dollars * massiv[4];
			cout << itog5;
			break;
		}

		case 6:
		{
			itog6 = dollars * massiv[5];
			cout << itog6;
			break;
		}

		case 7:
		{
			itog7 = dollars * massiv[6];
			cout << itog7;
			break;
		}

		case 8:
		{
			itog8 = dollars * massiv[7];
			cout << itog8;
			break;
		}

		case 9:
		{
			itog9 = dollars * massiv[8];
			cout << itog9;
			break;
		}

		case 10:
		{
			itog10 = dollars * massiv[9];
			cout << itog10;
			break;
		}

		case 11:
		{
			itog11 = dollars * massiv[10];
			cout << itog11;
			break;
		}

		case 12:
		{
			itog12 = dollars * massiv[11];
			cout << itog12;
			break;
		}

		default:
			cout << "выберите верный месяц с 1 по 12";

		}
return 0;
}
