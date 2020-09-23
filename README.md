<div align="center">

## Riotblade's Simple Calculator


</div>

### Description

Just a little calculator, might be helpful in the function department.
 
### More Info
 
Contains some area formulas just for helping you out.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Kevin Huang](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/kevin-huang.md)
**Level**          |Beginner
**User Rating**    |3.7 (11 globes from 3 users)
**Compatibility**  |C\+\+ \(general\)
**Category**       |[Math](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math__3-12.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/kevin-huang-riotblade-s-simple-calculator__3-6196/archive/master.zip)

### API Declarations

<iostream>


### Source Code

```
#include <iostream>
#include <stdlib.h>
using namespace std;
int main(int argc, char *argv[])
{
 int choices;
 long int a,b,c;
 std::cout << "Hi, welcome to Riotblade's calculator.\n";
 std::cout << "Select what you want to do.\n";
 std::cout << "(1)\tAdd\n";
 std::cout << "(2)\tSubtract\n";
 std::cout << "(3)\tDivide\n";
 std::cout << "(4)\tMultiply\n";
 std::cout << "(5)\tFormulas\n";
 std::cout << "(6)\tQuit\n";
 std::cin >> choices;
 switch (choices)
 {
 case 1:
  std::cout << "Enter two numbers.\n";
 std::cin >> a;
 std::cin >> b;
 c=(a+b);
 std::cout << "Your answer is " << c << ".\n";
 break;
 case 2:
 std::cout << "Enter two numbers.\n";
 std::cin >> a;
 std::cin >> b;
 c=(a-b);
 std::cout << "Your answer is " << c << ".\n";
 break;
 case 3:
 std::std::cout << "Enter two numbers.\n";
 std::cin >> a;
 std::cin >> b;
 c=(a/b);
 std::cout << "Your answer is " << c << ".\n";
 break;
 case 4:
 std::cout << "Enter two numbers.\n";
 std::cin >> a;
 std::cin >> b;
 c=(a*b);
 std::cout << "Your answer is " << c << ".\n";
 break;
 case 5:
 std::cout << "Area Formulas\n";
 std::cout << "Square: a*a\n";
 std::cout << "Rectangle: a*b\n";
 std::cout << "Parallelogram: base*height\n";
 std::cout << "Trapezoid: Height/2(b1+b2)\n";
 std::cout << "Circle: Pi*Radius squared\n";
 std::cout << "Ellipse: pi*r1*r2\n";
 std::cout << "Triagle: 1/2*b*h\n";
 std::cout << "Equillateral Triangle: Squareroot of 3/4 * (a squared)\n";
 break;
 case 6:
 abort();
 break;
 }
 system("PAUSE");
 return 0;
}
```

