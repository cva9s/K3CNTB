# K3CNTB
//code starts from here
#include <iostream>
using namespace std;

int main() {
    long n,k,arr[1000],i,count=0;
    cin>>n>>k;
    for(i=0;i<n;i++)
    {
        cin>>arr[i];
        if(arr[i]>=k)
        {
            count++;
        }
    }
