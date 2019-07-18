#include<iostream>
using namespace std;

int main()
{
    
    //While loop -- Sentinel-controlled
    int x=0;
    while(x !=99){
        cout << "Enter a number:" <<endl;
        cin >> x;
    }
    cout<<"Loop ended"<<endl;
    
    //do-while
    int y=0;
    do{
        cout<<"Enter a number:";
        cin>>y;
    }while(y !=99);
    cout<<"Do-while loop ended."<<endl;
    return 0;
}
