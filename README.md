# Cplus2.0_whileloop-if
using continue statement

#include <iostream>  
using namespace std;
 
int main() {
   int i = 1;
   while (i <= 7) {
      if (i == 4) {//the (4) num. is not executed
         i++;
         continue;
      }
      cout << i << "\n";
      i++;
   }
}
 output:
 1
 2
 3
 5
 6
 7 */
