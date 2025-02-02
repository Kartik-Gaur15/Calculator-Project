# Calculator-Project
#include <iostream>

int main()
{
    int a=0,b=0,c=0,d=0;
    std::cout<<"Welcoke to the simple calculator your request is our commnd";
    std::cout<<"\n";
    std::cout<<"Enter 2 numbers to start with the opertions";
    std::cin >> a>>b;
    std::cout<<"Press 1 for Addition (+)";
    std::cout<<"Press 2 for Substraction (-)";
    std::cout<<"Press 3 for Multiplication (*)";
    std::cout<<"Press 4 for Division (/)";
    std::cin >> c;
    if(c==1)
    {
        d=a+b;
        std::cout<<d;
    }
    if(c==2)
    {
        if(a>b)
        {
            d=a-b;
            std::cout<<d;
        }
        else
        {
            d=b-a;
            std::cout<<d;
        }
    }
    if(c==3)
    {
        d=a*b;
        std::cout<<d;
    }
    if(c==4)
    {
        d=a/b;
        std::cout<<d;
    }
    

    return 0;
}
