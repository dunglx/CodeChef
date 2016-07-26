#include <bits/stdc++.h>

using namespace std;

typedef long long ll;
typedef vector<long long> vi;

bool myfunction (ll i, ll j) {return (i>j);} 

int main() {
	// your code goes here
    long i,j,N,temp;
    ll max;
    
    cin >> N;
    
    vi myvector;
    
    for (i=0;i<N;i++)
    {
        cin >> temp;
        myvector.push_back(temp);
    }
    
    sort (myvector.begin(),myvector.end(),myfunction);
    
    max = myvector.at(0);
    
    for(i=0;i<N;i++)
    {
        if ((myvector.at(i)*(i+1))>max) max = myvector.at(i)*(i+1);
    }
    
    cout << max;
    	
	return 0;
}
