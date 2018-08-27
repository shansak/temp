#include<iostream>
using namespace std;

template<class A,class B,class C>
class num{
private:
    A x;
    B y;
    C z;
public:
    num(A u,B v,C w)
    {
        x=u;
        y=v;
        z=w;
    }
    void show()
    {
        cout<<x<<" "<<y<<" "<<z;
    }


};
int main()
{
    num<int,float,int>num1(34,34.6,34);
    num1.show();
    cout<<endl;
    num<char,int,string>num2('w',56,"nitin");
    num2.show();
}
