#include <iostream> 
using namespace std;
// Class definition
class Calculator
{
private:
float a, b;
public:
// Function to accept values
void getData(float x, float y)
{
a = x; 
b = y;
}
// Inline function for addition
inline float add()
{
return a + b;
}
// Inline function for subtraction
inline float subtract()
{
return a - b;
}
// Inline function for multiplication
inline float multiply()
{
return a * b;
}
// Inline function for division
inline float divide()
{
return a / b;
}
};
// Main function
int main()
{
Calculator calc;
float x, y;
// Accept input from user
cout << "Enter two numbers: ";
cin >> x >> y;
// Pass values to object
calc.getData(x, y);
// Display results
cout << "\nAddition = " << calc.add();
cout << "\nSubtraction = " << calc.subtract();
cout << "\nMultiplication = " << calc.multiply();
cout << "\nDivision = " << calc.divide();
return 0; // End of program
}
