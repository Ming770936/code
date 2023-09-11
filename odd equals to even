#include <iostream>
#include<bits/stdc++.h>
using namespace std;

string s;

bool judge(string s)
{
    int odd = 0;
    int even = 0;
    for(int i=0; i<s.size(); i++)
    {
        if(i%2==0)
            odd += s[i]-'0';
        else
            even += s[i]-'0';
    }
    return odd == even;
}

int main()
{
    int a, b;
    int num = 0;
    cin >> a >> b;

    for(int i=a; i<=b; i++)
    {
        s = to_string(i);
        num += judge(s);
    }

    cout << num << endl;
    return 0;
}
