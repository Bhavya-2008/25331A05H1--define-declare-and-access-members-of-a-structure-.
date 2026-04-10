# 25331A05H1--define-declare-and-access-members-of-a-structure-.
#include<stdio.h>
struct student {
    int rollno ;
    char name[60];
    float marks ;
};
int main()
{
    struct student s;
    s.rollno =111;
    printf ("enter name");
    scanf ("%s",s.name) ;
    printf ("enter marks");
    scanf ("%f",&s.marks);
    printf("\n student details\n");
    printf("rollno:%d\n",s.rollno);
    printf("name: %s\n",s.name);
    printf("marks:%2f\n",s.marks);
    return (0);
}
