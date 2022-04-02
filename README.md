# class-in-c-
class in c++ inside class outside class define
#include<iostream>
using namespace std;
class student
{
private:
   char name[20];
   int age;
   
public:
   void getdata();
   void display()
   {
       cout<<"name"<<name<<endl;
       cout<<"age"<<age<<endl;
   }
};
void student :: getdata(void)
{
    cout<<"enter name =";
    cin>>name;
    cout<<"enter age =";
    cin>>age;
}
int main()
{
    student stu;
    stu.getdata();
    stu.display();
    return 0;
}


