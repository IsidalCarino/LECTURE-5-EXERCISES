# Biography
```
#include <iostream>
#include <string>
using namespace std;
int main() 
{
    string age, address, name;

    cout << "Enter your name: " << endl;
    cin >> name;
    cout << "Enter your age: " << endl;
    cin >> age;
    cout << "Enter your address: " << address << endl;
    cin >> address;
    cout << "Your name is: " << name << endl;
    cout << "Your age is: " << age << endl;
    cout << "Your address is: " << address << endl;
}
```
# Temperature
```
#include <iostream>
using namespace std;
int main()
{
    double a; //note: use double instead of int cuz int is for whole number
    double b;
    cout << "Fahrenheit to Celsus (enter a number)" << endl;
    cin >> a;
    b = (a - 32) * 0.5556;
    cout << "Converted to Celcius is: " << b << endl;
}
```
# Temperature 2
```
#include <iostream>
using namespace std;
int main()
{
    double a, b;
    cout << "Celsius to Fahrnheit (enter a number)" <<endl;
    cin >> a;
    b = (a * 1.8) + 32;
    cout << "Converted Fahrenhiet is: " << b << endl;
}
```
# Circles
```
#include <iostream>
using namespace std;
int main()
{
    double r, a, c;
    cout << "Enter the radius of the circle" << endl;
    cin >> r;
    a = 3.14 * r * r;
    c = 2 * 3.14 * r;
    cout << "area of circle : " << a << endl;
    cout << "circumference  of circle is: " << c << endl;
}
```
# Rectangle Triangle Square
```
#include <iostream>
using namespace std;
int main()
{
    double length, width, rectangle, triangle, square;
    cout << "Calculate the area of Rectangle, Triangle and Square." << endl;
    cout << "Enter length: " << endl;
    cin >> length;
    cout << "Enter width: " << endl;
    cin >> width;

    rectangle = length * width;
    triangle = (length * width) * 0.5;
    square = length * length;

    cout << "Area of rectangle : " << rectangle << endl;
    cout << "Area of triangle: " << triangle << endl;
    cout << "Area of  square: " << square <<endl;
}
```

