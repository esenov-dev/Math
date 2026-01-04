#include <iostream>
#include <cmath>

using namespace std;
int main()
{
  double x, y, z, a, b, c, s;
  cout << "x, y, z: " <<endl;
  cin >> x >> y >>z;
  a = 2 * cos(x - (2. / 3.));
  b = (1. / 2.) + pow(sin(y), 2);
  c = 1 + pow(z, 2) / (3 - ((pow(z, 2))) / 5.);
  s = (a / b) * c;
  cout << "Result s= " << s << endl;
  return 0;
}
