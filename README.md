#include <bits/stdc++.h>
using namespace std;
 
int main()
{
 
    // Initializing a vector of string type
    vector<string> vec = { "Geeks", "For", "Geeks" };
 
    vec.clear();
    for (int i = 0; i <= (int)vec.size() - 1; i++)
        cout << vec[i] << ' ';
 
    cout << "Geeks For Geeks";
    return 0;
}
