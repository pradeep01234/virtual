# virtual
#include<iostream>

using namespace std;

class parent{
    public:
        virtual void merriage(){
            cout<<"marry depika otherwise nikal sale"<<endl;
        }
};

class child:public parent{
  public:
    void merriage(){
        cout<<"Nahi...................."<<endl;
    }
};

int main(){
    child c;
    parent *p;
    p=&c;
    p->merriage();

    
    
    return 0;
}
