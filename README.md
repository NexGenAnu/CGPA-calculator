# CGPA-calculator
In this you can can calculate your cgpa and according to that cgpa you will receive your grade and student category

#include<iostream>
using namespace std;
int main(){
    float total_sgpa;
    float cgpa;
    float marks_1, marks_2, marks_3, marks_4, marks_5, marks_6, marks_7, marks_8;
    cout << "Enter Your Semester Wise Marks (SGPA)" << endl;
    cin >> marks_1 >>  marks_2 >>  marks_3 >>  marks_4 >>  marks_5 >>  marks_6 >> marks_7 >> marks_8;
    total_sgpa = marks_1 + marks_2 + marks_3 + marks_4 + marks_5 + marks_6+ marks_7+ marks_8;
    cgpa = total_sgpa/8;
    cout << "Your CGPA : " << cgpa <<endl;

    if(cgpa==10)
    {
        cout<<"You are a outstanding Student And your Grade is A+" << endl;
    }
    else if(cgpa>=9 && cgpa < 9.9)
    {
        cout<<"You are a Brillant Student And your grade is A" << endl;
    }
    else if(cgpa>=8 && cgpa < 8.9)
    {
        cout<<"You are a Very Good Student And your grade is B+" << endl;
    }
    else if(cgpa>=7 && cgpa < 7.9)
    {
        cout<<"You are a GOOD Student And your grade is B" << endl;
    }
    else if(cgpa>=6 && cgpa < 6.9)
    {
        cout<<"You are a AVERAGE Student And your grade is C+" << endl;
    }
    else if(cgpa>=5 && cgpa < 5.9)
    {
        cout<<"You are a BELOW AVERAGE Student And your grade is C" << endl;
    }
    else if(cgpa>=4 && cgpa < 4.9)
    {
        cout<<"You are a Marginal Student And your grade is D" << endl;
    }
    else if(cgpa>=3 && cgpa < 3.9)
    {
        cout<<"You are a EXPOSED + FAIL Student And your grade is F" << endl;
    }
    else{
        cout << "YOU ARE NOT GIVEN EST'S OR REGISTERD FOR SEMESTER " << endl;
    }
    return 0;
}
