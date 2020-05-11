#include<iostream>
using namespace std;
class polymorph
{
float length,width,height,radius;
public:void volume(float);
void volume(float,float);
void volume(float,float,float);
};
void polymorph::volume(float a)
{
float vol;
radius=a;
vol=(4*3.14*radius*radius)/3;
cout<<"the volume of the sphere"<<vol<<endl;
};
void polymorph::volume(float a,float b)
{
float vol;
radius=a;
height=b;
vol=3.14*radius*radius*height;
cout<<"the volume of the cylinder:"<<vol<<endl;
};
void polymorph::volume(float a,float b,float c)
{
float vol;
length=a;
width=b;
height=c;
vol=length*width*height;
cout<<"the volume of the rectangular prism:"<<vol<<endl;
}
int main()
{
polymorph v;
float l,w,h,r;
cout<<"enter the values of l,w,h,r:";
cin>>l>>w>>h>>r;
v.volume(r);
v.volume(r,h);
v.volume(l,w,h);
return(0);
}
