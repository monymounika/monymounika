- š Hi, Iām @monymounika
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
monymounika/monymounika is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include<bits/stdc++.h>
using namespace std;
int main()
{
int n,i,count=1;
cout<<"enter any number";
cin>>n;
for(i=2;i<n/2;i++)
{
if(n%i==0)
{
cout<<"not prime number";
count=0;
break;
}
}
if (count)
{
cout<<"prime number";
}
return 0;
}
