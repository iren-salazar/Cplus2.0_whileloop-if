# Cplus2.0_whileloop-if
using continue statement printing numbers

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

                   
 #include <iostream>  
using namespace std;
 
int main() {
   int i = 1;
   while (i <= 10) {//1 to 10
      if (i == 5) {//ang i=10 then (5) to (10) will not be executed.
         continue;
      }
      cout << i << "\n";
      i++;
   }
}
 /*output:
   1
   2
   3
   4      */            
                   
                   
                   
