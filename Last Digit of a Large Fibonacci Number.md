```cpp
#include<iostream>
#include<vector>
using namespace std;
int main()
{
    long long n,t1=0,t2=1;
    cin>>n;

    if(n<=1)
        cout<<n<<endl;

    vector <long long> arr ={0,1};
    for(int i =2;i<=n;i++)
    {
        arr.push_back(arr[i-1]+arr[i-2]);
    }

    for(int j=n-1;j>=1;j--)
    {
        cout<<arr[j]<<" ";
        break;
    }
}
```
