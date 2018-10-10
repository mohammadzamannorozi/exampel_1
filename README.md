# exampel_1
the exampel_1 in c++ 
#include "person.h"
using namespace tzama;
person::person()
{
}
int set_age(int _age)
{

}

int get_age(int _age_2)
{

}

int set_weight(int _weight)
{

}

int get_weight(int _weight_2)
{

}

#ifndef PERSON_H
#define PERSON_H
#include <iostream>
#include <cstring>

using namespace std;

namespace tzama {



enum selection{
    mother,
    father
};

class person
{
private:
    string age;
    string weight;


public:
    string job;
    string classname;
    string name;
    string money;
    string phonenumber;

    int set_age(int);
    int get_age(int);

    int set_weight(int);
    int get_weight(int);

    person();
};


}
#endif // PERSON_H

#include <iostream>
#include <cstring>
#include "person.h"
using namespace std;
using namespace tzama;
int main()
{
    person p[10];
    for (int ctr = 0;ctr < 10;ctr++)
    {
        p[ctr].name;
        p[ctr].job;
        p[ctr].classname;
        p[ctr].money;
        p[ctr].phonenumber;
    }

    int num;
    cout << "please enter a namber";
    cin >> num;
    if (num >= 1 & num <= 10)
    {
        switch (num) {
        case 1:

            break;
        case 2:

            break;

        case 3:

            break;

        case 4:

            break;

        case 5:

            break;

        case 6:

            break;

        case 7:

            break;

        case 8:

            break;

        case 9:

            break;

        case 10:

            break;

        }


    }
    else
        cout << "oooooooooooopppps ";
    return 0;
}








/*
     cout << "your  student = " << p[num - 1].name << endl;
     cout << "your  school  = " << p[num - 1].school << endl;

*/
