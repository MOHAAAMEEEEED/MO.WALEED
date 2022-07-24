```cpp
#include <iostream>
using namespace std;
int main() 
{
    int a, b, least;
    cin>>a>>b;
    if(a>b)
    least = a;
    else
    least = b;
    while(1) 
    {
        if( least % a==0 && least % b==0 ) 
        {
            cout<<"The LCM of "<<a<<" and "<<b<<" is "<<least;
            break;
        }
    least++;
    }
    return 0;
}
```
