#include <iostream>
using namespace std;
int main()
{
cout << "Home task #7.2.1\n";
int number, digit, userChoice, nDigits, nZeros;
float sum, mean;
sum = 0;
nDigits = 0;
nZeros = 0;
cout << "Please, enter your number:\n";
cin >> number;
do {
cout << "Your choice:\n";
cout << "1 - number of digits\n";
cout << "2 - sum of digits\n";
cout << "3 - mean\n";
cout << "4 - number of zeros\n";
cout << "5 - quit\n";
cin >> userChoice;
while (number > 0)
{
digit = number % 10;
sum += digit;
nDigits++;
if (digit == 0)
  {
nZeros++;
}
number = number / 10;
}
mean = sum / nDigits;
switch (userChoice) {
case 1:
{
cout << "Calculating the number
of digits...\n";
cout << nDigits <<"\n";
break;
}
case 2:
{
cout << "Calculating the sum
of digits...\n";
cout << sum <<"\n";
break;
}
case 3:
{
cout << "Calculating the mean...\n";
cout << mean <<"\n";
break;
}
case 4:
{
cout << "Calculating the number
of zeros...\n";
cout << nZeros <<"\n";
break;
  }
case 5:
{
cout << "See you!";
break;
}
default:
cout << "Wrong menu item!";
}
} while (userChoice != 5);
return 0;
}
