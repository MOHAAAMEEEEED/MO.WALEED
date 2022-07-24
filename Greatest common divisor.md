```cpp
#include<iostream>
using namespace std;
int main()
{
    int A,B;
    cin>>A>>B;
    int low=min(A,B);

    for(int i=low;i>1;i--)
    {
        if(A%i==0 && B%i==0)
        {
            cout<<i<<endl;
            break;
        }
    }
}

```
