#include<iostream>
using namespace std;
class shape
{
public:
    float d1,d2;
    shape(float d1,float d2)
    {
        this->d1=d1;
        this->d2=d2;
    }
    float area()
    {
        return 0;
    }
};
class triangle:public shape
{
public:
    triangle(float d1,float d2)
    :shape(d1,d2)
    {
        this->d1=d1;
        this->d2=d2;

    }
    float area()
    {
        return 0.5*d1*d2;
    }
};
class rectangle:public shape
{
public:
    rectangle(float d1,float d2)
    :shape(d1,d2)
    {
        this->d1=d1;
        this->d2=d2;
    }
    float area()
    {
        return d1*d2;
    }
};
int main()
{
    triangle t(10,20);
    rectangle r(10,20);
    cout<<"area of the triangle: "<<t.area()<<endl;
    cout<<"area of the rectangle: "<<r.area();
    return 0;
}
