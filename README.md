#include <iostream>
#include <cstdio>
using namespace std;

int main() {
    // Complete the code.
    int a,b;
    int x=0;
    cin>>a;
    cin>>b;
     for(int x=a;x<=b;x++)
    {
    if(x==1)
    cout<<"one"<<endl;
    else if(x==2)
    cout<<"two"<<endl;
    else if(x==3)
    cout<<"three"<<endl;
    else if(x==4)
    cout<<"four"<<endl;
    else if(x==5)
    cout<<"five"<<endl;
    else if(x==6)
    cout<<"six"<<endl;
    else if(x==7)
    cout<<"seven"<<endl;
    else if(x==8)
    cout<<"eight"<<endl; 
    else if(x==9)
    cout<<"nine"<<endl;    
    else if(x>9)
        {
            if(x%2==0)
            cout<<"even"<<endl;
            else {
            cout<<"odd"<<endl;
            }
        }

    }
    
        
    
    return 0;
}
