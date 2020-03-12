# divisibity
#include <iostream>
 
using namespace std;
 
int main() {
 
   int N;
    cin>>N;
    
    long data[N];
    for(auto i=0; i<N; i++){
        cin>>data[i];
    }
    if(data[N-1]%10==0)
    cout<<"Yes\n";
    else
    cout<<"No\n";
    
    // write your code here
    // ans = 
    
    
    
    
    return 0;
}
