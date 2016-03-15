# pierwszy
// Krzysztof Pęczek
#include <stdio.h>
#include <iostream>


using namespace std;
int main(int argc, char *argv[])
{
    int a=1, b=1, c;
    

    printf("fibinacziego:\n");
    printf("0\n");
    printf("1\n");
    printf("1\n");
    	for (int i = 0; i < 9; ++i)
{
   c=a+b;
   a=c;
   b=a-b;
   
   cout<< c<< endl;
} 

printf("inny ciąg:\n");

int d=1, e;
      for (int i = 0; i < 9; ++i)
{
   e=d+3;
   cout<< e<<endl;
   d++;

  


}

}


